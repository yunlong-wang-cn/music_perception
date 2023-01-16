# Sound2Note

## 1. Introduction 
This is a RosNode to translate the sound signal to western notation, based on the base version from Michael. 
## 2. Installation
### 2.1 Declaration
This installation instruction has been currently verified only at the lab compute. 

### 2.2 Installation of python virtual environment
1. Come to your project position, the build the python virtualenv: `python -m venv env_sound2note --system-site-packages && source env_sound2note/bin/activate`.
2. Build you ros workspace: `mkdir -p ws_soud2note/src && cd ws_soud2note/src`. 
3. Download the code: `git clone https://github.com/yunlong-wang-cn/music_perception.git`.
4. Install the python requirements: `pip install librosa`, and the `pip install crepe`

### 2.3 Build ros workspace
1. Activate the ros environment on the computer: `source /opt/ros/noetic/setup.bash`, or write this command into `~/.bashrc`.
2. Because the `audio_common` in lab computer is out of date, so you need to download it and rebuild, therefore `git clone https://github.com/ros-drivers/audio_common.git`.
3. Try to build the package: `catkin build`

