# apkmagician

Easily transfer an installed apk from your device, patch it and install the patched version.

Currently supports following patches:
- Enable [WebView debugging](https://developers.google.com/web/tools/chrome-devtools/remote-debugging/webviews) by automatically patching the decompiled smali for LAUNCHER activity class
- Inject [Frida Gadget](https://frida.re/docs/gadget/) into an already included native library (TODO: Use `System.loadLibary` instead?)

Non-python requirements:
- [apktool](https://ibotpeaches.github.io/Apktool/)
- [uber-apk-signer](https://github.com/patrickfav/uber-apk-signer)
- [adb](https://developer.android.com/studio/command-line/adb)

## TODO
- Handle split apks (see https://platinmods.com/threads/how-to-turn-a-split-apk-into-a-normal-non-split-apk.76683/)
