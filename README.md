This is a program meant to test the functionality of the C++ Debugger for Visual Studio Code.
In order to run this code, you need to install MSYS2 and follow download instructions as mentioned by the installer. Then you need to add the "msys64/ucrt64/bin" path when entering:
1) "Edits Environment Variables"
2) Click on PATH then click edit
3) Paste the file path to ucrt64/bin
4) Press "ok" twice and close the window

Go to the MSYS64 URCRT64 command prompt and install the following libraries and dependancies:
1) Check if all folders are synced up: $pacman -Syu
2) If confirmation is needed then type and enter "Y"
3) Enter "$pacman -S mingw-w64-ucrt-x86_64-gcc"
4) Accept any confirmation request by entering "Y"

Ensure that the C++ Debugger is installed in your Visual Studio Code and reset after installation!

5) Check if "g++" is recognized by writing "$which g++". If you get /ucrt64/bin/g++ then g++.exe is recognized and you can continue
6) In the UCRT64 Command Prompt, Navigate to your workplace folder and write "g++ {YOUR PROGRAM}.cpp -o Test
7) write "./test" to see the system output.