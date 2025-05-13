Adapted from [Arm Manipulation in Isaac Sim Using MoveIt Servo](https://www.youtube.com/watch?v=-jqepxgzs_I); code downloaded on 2025-MAY-13.

The code was modified so that the end effector moves according to how we manipulate the Spacemouse (ie pushing Spacemouse forward moves the end effector forward instead of backward, etc).

Requires (apart from those stated in the video):
- [joystick drivers](https://github.com/ros-drivers/joystick_drivers)

# Usage Guide
1. Clone `joystick drivers` repo and follow the installation instructions.
2. Clone this repo.
3. On one terminal, navigate to `joystick drivers` repo, source it, and run `ros2 run spacenav spacenav_node`.
4. On one terminal, navigate to this repo, build it, source it and run `ros2 launch wx250s_moveit_config arm_joy_control.launch.py`.


# Todo
- [] Practice how to use mouse/ adjust sensitivity to minimize unintended motion