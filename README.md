# with-joy-con

# 動作環境
< ハードウェア >
- Turtlebot2
- SwitchのJoy-Con

< ソフトウェア >
- ROS
- Ubuntu 18.04
- Python 2.7


# 実行手順
< サーバサイド >
  1. いつもの要領で、Turtlebot関係のROSを立ち上げます。
  1. Turtlebotと繋がった機器で、[move.py](./src/move.py)を実行します。

< クライアントサイド >  
  1. UbuntuにBluetoothで、Joy-Conを接続します。
  1. [joycon_client.py](./src/joycon_client.py)を実行します。
