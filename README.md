LWJGL - Lightweight Java Game Library For M1
======



The Lightweight Java Game Library (LWJGL) is a solution aimed directly at professional and amateur Java programmers alike to enable commercial quality games to be written in Java. 
LWJGL provides developers access to high performance crossplatform libraries such as OpenGL (Open Graphics Library), OpenCL (Open Computing Language) and OpenAL (Open Audio Library) allowing for state of the art 3D games and 3D sound.
Additionally LWJGL provides access to controllers such as Gamepads, Steering wheel and Joysticks.
All in a simple and straight forward API.

Website: [http://lwjgl.org](http://lwjgl.org)
Forum: [http://lwjgl.org/forum](http://lwjgl.org/forum)
Bugs/Suggestions: [https://github.com/LWJGL/lwjgl/issues](https://github.com/LWJGL/lwjgl/issues)

Compilation
-----------

LWJGL requires a JDK and Ant installed to compile, as well as your platforms native compiler to compile the JNI.

### Building on Mac M1

Install the [Java 8 for arm64](https://www.azul.com/downloads/?version=java-8-lts&os=macos&architecture=arm-64-bit&package=jdk) provided by Zulu.

Find where it was installed, usually in `/Library/Java/JavaVirtualMachines/zulu-8`.

In that folder open `Contents` and then copy the path of the `Home` folder.

Replace `jhome` with the path you just copied.

```
* JAVA_HOME=jhome ant generate-all
* JAVA_HOME=jhome ant compile
* JAVA_HOME=jhome ant compile_native
```
