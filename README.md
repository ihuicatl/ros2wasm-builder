# ROS2WASM Builder

This action cross-compiles a ROS 2 package to WebAssembly and uploads the built files as artifacts.

## Usage

```yaml
- steps:
    uses: ihuicatl/ros2wasm-builder@0.1.2
    with:
        package: 'the_target_package'
        ros_distro: 'humble'
        debug_mode: false
```
