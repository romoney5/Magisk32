![](docs/images/logo.png)

#### This is not an officially supported Google product and is not endorsed by topjohnwu or HuskyDG.

## Introduction

Magisk Zygote64_32 is a modification of Magisk, which is a suite of software primarily designed as a root solution for multilib Android devices that are Zygote64 only.<br>
Some highlight features:

- **MagiskSU**: Provide root access for applications
- **Magisk Modules**: Modify read-only partitions by installing modules
- **MagiskBoot**: The most complete tool for unpacking and repacking Android boot images
- **Zygisk**: Run code in every Android applications' processes

Added with [Magisk Zygote64_32](https://github.com/Namelesswonder/Magisk/tree/32bit) is:

- **Zygote64_32**: Enables secondary Zygote process to allow 32-bit applications to start

Further added with [Magisk Delta 32-bit](https://github.com/Namelesswonder/Magisk/tree/delta-32bit) is:

- **early-mount.d**: Mount files before the init process is ran
- **init.rc injection**: Inject rc scripts without having to rebuild the initrd
- **Systemless file removal**: Remove file and folders systemlessly
- **SuList**: Hides Magisk binaries by default and only whitelisted processes can use Magisk
- **Maru**: Zygisk implementation using Native Bridge

Currently only the Pixel 7 and Pixel 7 Pro are officially supported by this project.

Currently only Magisk Zygote64_32 has full support, with Magisk Delta 32-bit being offered _as-is_.

## Sources

The sources for [Magisk Zygote64_32 are available on the page you are reading this from right now](https://github.com/Namelesswonder/Magisk/tree/32bit).

The sources for [Magisk Delta 32-bit are available in the delta-32bit branch](https://github.com/Namelesswonder/Magisk/tree/delta-32bit).

## Downloads

[My GitHub download repository](https://github.com/Namelesswonder/magisk-files) has the downloads of the Magisk app for both Magisk Zygote64_32 and Magisk Delta 32-bit.

## Useful Links

- [Installation Instruction](https://topjohnwu.github.io/Magisk/install.html)
- [Building and Development](https://topjohnwu.github.io/Magisk/build.html)
- [Magisk Documentation](https://topjohnwu.github.io/Magisk/)
- [Zygisk module sample](https://github.com/topjohnwu/zygisk-module-sample)

## Bug Reports

**Only bug reports from Magisk Zygote64_32 builds will be accepted, as I am not running Magisk Delta 32-bit**

For installation issues, upload both boot image and install logs.<br>
For bootloops or Magisk issues, upload boot logcat or dmesg.<br>

## Translation Contributions

Default string resources for the Magisk app and its stub APK are located here:

- `app/core/src/main/res/values/strings.xml`
- `app/stub/src/main/res/values/strings.xml`

Translate each and place them in the respective locations (`[module]/src/main/res/values-[lang]/strings.xml`).

## License

    Magisk, including all git submodules are free software:
    you can redistribute it and/or modify it under the terms of the
    GNU General Public License as published by the Free Software Foundation,
    either version 3 of the License, or (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.
