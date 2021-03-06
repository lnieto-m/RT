# RT

The 42 Raytracer project.

Project done with the Graphics Library GTK.

## Usage

GTK+ and the GSL - GNU scientific library must be installed on your device.

Build and Run :
```
make && ./rt [file]
```

File example :
```
resolution : 1280 720

ambient_light : 0.1

material_type : metal
specular_power : 500
specular : 600

object : light
pos : 300 -200 -500
color : 0.5 0.5 0.5

object : light
pos : -300 -200 -500
color : 0.75 0.75 0.75


object : camera
pos : 0 -100 -750
angle : 0 0 0

object : plane
pos : 0 -1 0
radius : 0
material : metal
color : 1 1 1

object : plane
pos : 0 0 -1
radius : 100
material : metal
color : 0 0 1

object : sphere
pos : -88 -20 -40
radius : 20
material : metal
color : 1 0 0

object : sphere
pos : 95 -20 -40
radius : 20
material : metal
color : 0 1 0

object : cone
pos : 50 -30 0
radius : 20
angle : 0 0 0.5
material : metal
color : 1 1 0

object : cylinder
pos : -50 0 0
radius : 20
angle : 0 0 -0.75
material : metal
color : 1 0 0.5
```

Result :
![sujet1](https://raw.githubusercontent.com/lnieto-m/RT/master/screenshots/sujet1.jpg)

### Others examples

A minion :
![minion](https://raw.githubusercontent.com/lnieto-m/RT/master/screenshots/minion.jpg)

Bomberman :
![bomberman](https://raw.githubusercontent.com/lnieto-m/RT/master/screenshots/bomberman.jpg)

The solar system :
![solar system](https://raw.githubusercontent.com/lnieto-m/RT/master/screenshots/solar_system.jpg)
