[]()

# Project Team : Wls sisullivan

<p align="center">
  <img width="700" height="350" src="https://user-images.githubusercontent.com/71277820/132127880-b20c1869-dfa0-4aea-ad04-9a5fe2b14d9d.PNG">
</p>


## Introduce

위 로봇은 시각, 청각능력 없이 오직 촉각만을 느낄 수 있는 시청각 장애인들을 위해 만들어 졌으며, 로봇이 사용자의 특정한 손짓을 인식하여 사용자를 특정 장소까지 안전하게 인도하는 로봇이다.

## Demo youtube link

[![Video Label](https://user-images.githubusercontent.com/71277820/161438131-49853121-f4f7-4918-919d-9333d6604514.png)](https://www.youtube.com/watch?v=FCpgLseV2Cw)

## Workflow

<p align="center">
  Nomal mode
  
</p>


<p align="center">
  <img src="https://user-images.githubusercontent.com/71277820/132127678-ddb22169-bbcf-41c4-a4d3-b42b810b9990.PNG">
</p>

<p align="center">
   Emergency mode
  
  
</p>

<p align="center">
  <img src="https://user-images.githubusercontent.com/71277820/132127679-26793a11-db7d-486e-ba1f-610323179d84.PNG">
</p>


## Hardware Archtecture


![https://user-images.githubusercontent.com/71277820/132128891-1c86db73-4cc6-4690-b971-a1122bcf12d5.PNG](https://user-images.githubusercontent.com/71277820/132128891-1c86db73-4cc6-4690-b971-a1122bcf12d5.PNG)

## Software Archtecture

![https://user-images.githubusercontent.com/71277820/132128803-9cf4da9d-1bc5-4ff7-a755-14320d0988df.png](https://user-images.githubusercontent.com/71277820/132128803-9cf4da9d-1bc5-4ff7-a755-14320d0988df.png)

## Install

```bash
mkdir -p ~/catkin_ws/src
cd ~/catkin_ws/src
git clone <https://github.com/ggh-png/MR_2.git>

```

## Essential pakage install

```bash
cd ~/catkin_ws/src/MR_2
./essential_package_install.sh
source ~/.bashrc

```

## rebuild all

```bash
cd ~/catkin_ws/src/MR_2
./rebuild_all.sh

```

## build all

```bash
cd ~/catkin_ws/src/MR_2
./build_all.sh

```

# launch server

```bash
roscore
roslaunch MR_2_core MR_2_core.launch

```

# launch TP

## launch ui full size

```bash
cd ~/catkin_ws/src/MR_2
./launch_ui.sh

```

## launch ui max size

```bash
cd ~/catkin_ws/src/MR_2
./launch_ui_size_max.sh

```

# launch robot

```bash
source ~/catkin_ws/devel/setup.bash
roslaunch slam bringup.launch

```

## warning

> 해당 package는 ubuntu 18.04 ros melodic 환경에서 동작합니다.
(그외의 환경에서는 작동하지 않습니다.)
>
