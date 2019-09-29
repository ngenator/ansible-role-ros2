ros2
=========

Ansible role to install ROS2

Requirements
------------

None

Role Variables
--------------

ros_distribution: dashing
ros_configuration: desktop,desktop-full,ros-base


Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: ngenator.ros2, ros_packages: [] }

License
-------

MIT
