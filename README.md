# Carrot-boards
全自動走行台車の回路図です。
[Carrotの動画はこちら](https://www.youtube.com/watch?v=5gtot_12dCg&ab_channel=DDProjectII)


# Features

* STM32F7 Discovery用のボード
* KeyHolder FT234を使ったUSBシリアル変換器
* UI 操作板の基板データ　F4書き込みや、電源、リセットスイッチなどを載せる
* mainboard main基板　raspberryPiやSTM32F4が載ります

# Requirement

* Autodesk Eagleを用いて作成しました。

F4のプログラムは[こちら](https://github.com/rakuseirobot/Carrot-F4-motor)
RaspberryPiのプログラムは[こちら](https://github.com/rakuseirobot/Carrot-ROS-src)

# Note

mainboardに搭載されているSTM32F446に配線されているイーサネットICはLANコネクタを向きを逆に配置してしまったこととおそらく配線を間違ってしまったこともあり、実装すると3.3Vラインがショートしてしまうため注意してください。

# Author

* Shun Kayaki
* Kyushu institute of Technology
* shun@guetan.dev

# License

Copyright (c) 2019 Shun Kayaki
Released under the MIT license
