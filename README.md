android-m4
==========

An autotools script to help developing Android application

This script defines these functions:
 * ANDROID_PATH_PROG_NDK_BUILD
 * ANDROID_PATH_PROG_ANDROID
 * ANDROID_PATH_PROG_DX
 * ANDROID_PATH_PROG_KEYTOOL
 * ANDROID_PATH_PROG_AAPT
 * ANDROID_PATH_PROG_JARSIGNER
 * ANDROID_PATH_PROG_ZIPALIGN
 * ANDROID_PATH_PROG_EMULATOR
 * ANDROID_PATH_PROG_ADB

All these function prototypes are similar to:
ANDROID_PATH_PROG_ANDROID(found, not-found)
Where found and not-found are commands that will be run if the program is found, or not found.
In addition, an environment variable is declared containing the absolute path to the program.
In this case ANDROID will point to /opt/android-sdk/somewhere/android.
