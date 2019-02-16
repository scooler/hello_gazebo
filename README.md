# Hello Gazebo !

It's super simple Gazebo world.

```
gazebo ./world/world3.world
```

It uses a plugin which you can build with

```
cd build
cmake ../
make
```

OH - and I've also set a variable

```
export GAZEBO_PLUGIN_PATH=${GAZEBO_PLUGIN_PATH}:$(pwd)/build
```