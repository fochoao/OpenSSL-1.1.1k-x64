# OpenSSL 1.1.1k x64

OpenSSL 1.1.1k binaries for Windows 10, working in 64 bits.

# Binaries

High precision release, all algorithms and hashes work, including SHA3 512 bits, AES-XTS, AES-OFB, AES-GCM, etc...

# Where to place?

In program files, the same as it is here, You do not need to do anything, other than add said folders to PATH.

# Steps to perform

Step 1.
Open "File Explorer" -> Right Click "This PC" -> Click on "Properties" -> Click on "Advanced System Settings"

Step 2.
Click on "Environment variables" on tab "Advanced" -> Click "New" and Write on "Variable Name", "OPENSSLDIR", and on "Variable Value", "C:\Program Files\Common Files\SS\"

Step 3.
Click on "Environment variables" on tab "Advanced" -> Click "New" and Write on "Variable Name", "ENGINESDIR", and on "Variable Value", "C:\Program Files\OpenSSL\lib\engines-1_1\"

Step 4.
Now on "System Variables" find "Path", add these two folders, press on the button "New", add "C:\Program Files\Common Files\SS\" and "C:\Program Files\OpenSSL\lib\engines-1_1\"

# Release Version and Compilation

This compilation is special because it enables all kind of ways to encrypt data, program with OpenSSL, say with Python, PHP, etc... All algorithms, All hashes, and all ways to
issue certificates, I did this very carefully, not a single bug.
