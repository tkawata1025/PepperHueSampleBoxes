
Pepper から Philips HUE をコントロールするサンプルボックスです。

HUE PUT ボックスは HUE を点灯、消灯するボックスです。
HUE GET ボックスは HUE の点灯、消灯の情報を取得するボックスです。

それぞれボックスプロパティー HUE Bridge IPAddr に HUE ブリッジの IP アドレスを
authorized user id には登録し取得された user ID を設定します。

それぞれの値の取得方法は次を確認ください
http://www.developers.meethue.com/documentation/getting-started

このサンプルは requests モジュールを必要とします。

ディレクトリ PepperHueSampleBoxes 配下で次を実行し、モジュールをプロジェクトに取り込みます

pip install requests --target ./lib --no-compile

*****

提供物はすべてサンプルプログラムとお考えください。 耐久試験や、異常系の完全な動作確認テストは行っていません。

*****
