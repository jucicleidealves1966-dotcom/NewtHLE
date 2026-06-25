# NewtHLE: high-level emulator for iOS apps

**NewtHLE** is a high-level emulator for iOS apps. It runs on modern desktop operating systems and Android, and is a fork to TouchHLE.

The goal of this project is to run games from the early days of iOS:

* Currently: iPhone and iPod touch apps for iPhone OS 2.x and iPhone OS 3.0 iPhone OS 3.1, iPad apps (iPhone OS 3.2), iOS 4.
* Longer-term: iOS 5 to 10.
* [Never](https://github.com/touchHLE/touchHLE/issues/181#issuecomment-1777098259): 64-bit iOS.

# Thanks

We stand on the shoulders of giants. Thank you to:

* Everyone who has contributed to the project or supported any of its contributors financially.
* The authors of and contributors to the many libraries used by this project: [dynarmic](https://github.com/merryhime/dynarmic), [rust-macho](https://github.com/flier/rust-macho), [SDL](https://libsdl.org/), [rust-sdl2](https://github.com/Rust-SDL2/rust-sdl2), [stb\_image](https://github.com/nothings/stb), Imagination Technologies' [PVRTC decompressor](https://github.com/powervr-graphics/Native_SDK/blob/master/framework/PVRCore/texture/PVRTDecompress.cpp), [openal-soft](https://github.com/kcat/openal-soft), [hound](https://github.com/ruuda/hound), [caf](https://github.com/rustaudio/caf), [Symphonia](https://github.com/pdeljanov/Symphonia), [RustType](https://gitlab.redox-os.org/redox-os/rusttype), [the Liberation fonts](https://github.com/liberationfonts/liberation-fonts), [the Noto CJK fonts](https://github.com/googlefonts/noto-cjk), [rust-plist](https://github.com/ebarnard/rust-plist), [nibarchive](https://github.com/michaelwright235/nibarchive), [quick-xml](https://github.com/tafia/quick-xml), [gl-rs](https://github.com/brendanzab/gl-rs), [cargo-license](https://github.com/onur/cargo-license), [cc-rs](https://github.com/rust-lang/cc-rs), [cmake-rs](https://github.com/rust-lang/cmake-rs), [cargo-ndk](https://github.com/bbqsrc/cargo-ndk), [cargo-ndk-android-gradle](https://github.com/willir/cargo-ndk-android-gradle), [md-5 and sha1](https://github.com/RustCrypto/hashes), [yore](https://github.com/bonega/yore), [encoding_rs](https://github.com/hsivonen/encoding_rs), [corosensei](https://github.com/Amanieu/corosensei) and the Rust standard library.
* The Skyline emulator project (RIP), for [writing the tedious boilerplate needed to replace file management on newer Android versions](https://github.com/skyline-emu/skyline/blob/dc20a615275f66bee20a4fd851ef0231daca4f14/app/src/main/java/emu/skyline/provider/DocumentsProvider.kt).
* The [Rust project](https://www.rust-lang.org/) generally.
* The various people out there who've documented the iPhone OS platform, officially or otherwise. Much of this documentation is linked to within this codebase!
* The iOS hacking/jailbreaking community.
* The Free Software Foundation, for making libgcc and libstdc++ copyleft and therefore saving this project from ABI hell.
* The National Security Agency of the United States of America, for [Ghidra](https://ghidra-sre.org/).
* [GerritForge](http://www.gerritforge.com/) for providing free Gerrit hosting to the general public, including us.
* The many contributors to [Gerrit](https://www.gerritcodereview.com/).
* Many friends who took an interest in the project and gave suggestions and encouragement.
* Developers of early iPhone OS apps. What treasures you created!
* Apple, and NeXT before them, for creating such fantastic platforms.
