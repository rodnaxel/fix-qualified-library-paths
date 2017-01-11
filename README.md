**Description:**
Script to fix symlinks and lib paths on raspbian

**Using:**

```bash
cd /<path-to-folder-script>
./fixQualifiedLibraryPaths /<path-to-your-sysroot> /<path-to-toolchain>
```

**Example:**

```bash
cd ~/opt/cross-compile-tools
sudo ./fixQualifiedLibraryPaths /mnt/rasp-pi-rootfs/ ~/opt/gcc-4.7-linaro-rpi-gnueabihf/bin/arm-linux-gnueabihf-gcc
```

**Source**

[QtForum, user Lutfi88](https://forum.qt.io/topic/51542/qt-5-4-compile-problem-for-raspberry-pi-again/8)
