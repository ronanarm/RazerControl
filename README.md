# RazerControl

This is a GUI, which resides in your menubar. The icon is a razor-blade, which is - as you may guess - a intended pun. It uses the amazing work of [kprinssu](https://github.com/kprinssu/osx-razer-blade) which then has been forked by [dylanparker](https://github.com/dylanparker/osx-razer-led), who added the command line functionallity. My software then executes the needed shell commands.

![User Interface](readme_images/userinterface.png)

## Installation

Please check out the releases section of this repo, you can find binaries in the OSX app format there. Place it into your application folder and set it as a login item in system preferences > users & groups > login items, if you want to.

As already stated, this needs the dependency *osx-razer-led*, compiled (which you can easily do in xcode) as a binary in */usr/local/bin*. Don't forget to make it executable, by running *chmod +x osx-razer-led*. You can download precompiled binaries [here](https://github.com/dylanparker/osx-razer-led/releases).

## Future plans

- [x] Add a visual for sending commands
- [ ] Make the settings persistent over re-launch
- [x] Keeping the right order in dropdown item list
- [x] Fix slider positioning (length)
- [x] Add terminate button
- [ ] Implement update notifier
- [x] Package this as an OSX app
- [ ] Automatically download needed binary from repo
