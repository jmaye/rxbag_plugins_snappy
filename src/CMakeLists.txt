remake_ros_package(
  rxbag_plugins_snappy
  DEPENDS rospy roslib rxbag sensor_msgs mv_cameras
  DESCRIPTION "Rxbag plugins for snappy messages."
  EXTRA_RUN_DEPENDS libsnappy-python
)
