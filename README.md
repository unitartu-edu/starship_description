# starship\_description

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

ROS URDF description package for [Starship](https://starship.xyz) delivery robot that contains meshes and xacro files. This package is designed and licensed for educational purposes. The content has been created for [ROSi algkursus](https://sisu.ut.ee/rosak) at the University of Tartu.

## Setup (ROS Noetic)

```git clone https://github.com/unitartu-edu/starship_description```

```catkin build```

```source ~/catkin_ws/devel/setup.bash```

## Visualizing the robot in RViz
Open a terminal window and navigate to the ```starship_description/urdf``` folder

```roscd starship_description/urdf```

```roslaunch urdf_tutorial display.launch model:=starship.urdf.xacro```

## Acknowledgement

<table>
<tr border=0>
<td valign="middle">
  <img src="https://github.com/unitartu-remrob/.github/blob/main/profile/logo_HARNO_3lovi_est_rgb.png" class="center" height=100"/>
</td>
<td valign="middle">
  <img src="https://github.com/unitartu-remrob/.github/blob/main/profile/logo_ITA_rgb.png" class="center" height=60"/>
</td>
</tr>
</table>

Completed with the support by IT Academy Programme of Education and Youth Board of Estonia.
