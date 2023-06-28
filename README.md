# diffdrive_pico

This node is designed to provide a ros2_control hardware interface for an Pico to be used with a `diff_drive_controller` from `ros2_control`.
It is expected to communicate via serial and to have six motors, each with velocity control and position/velocity feedback.




It is based on the diffbot example from [ros2_control demos](https://github.com/ros-controls/ros2_control_demos/tree/master/example_2).
and https://github.com/joshnewans/diffdrive_arduino
