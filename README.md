Installation

Zum Installieren werden folgende Abhängigkeiten benötigt: OpenCV (>= 2.4), mavros, mavros_msgs, imutils

OpenCV : Installationsanleitung

Mavros: sudo apt-get install ros-indigo-mavros ros-indigo-mavros-msgs

imutils: 
imutils ist eine python Bibliothek, welche einfach mit pip installiert werden kann. 
pip kann mit dem Befehl sudo apt-get install python-pip installiert werden. 


Als nächstes muss ein catkin_workspace an beliebiger Stelle im System angelegt werden: 

mkdir <workspace_folder>
cd <workspace_folder>
mkdir src 
cd src 

catkin_init_workspace

Anschließend wird das Repository in den Workspace geklont und der Workspace gebaut:

git clone git@gitlab.com:SGimbel/MPSE-WS1617_B.git autonomous_driving

cd ../
catkin_make


