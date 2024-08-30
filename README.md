# Installation-Fest

## HomeBrew Install
1. Open Terminal
2. Use the below command: 
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
3. Installation Successful
4. Copy and Run two commands as next steps displayed post installation.

## Mingw-64 Install
1. In terminal: 
```
brew install mingw-w64
```

### gcc (Alternative)
1. In terminal: 
```
brew install gcc
```
2. To run c/c++ files use: 
```
gcc <program.c> -o <output_file>
./<output_file> <arguments ....>
```

## VSCode 
1. Go to: https://code.visualstudio.com/download
2. Select .zip folder for Apple Silicon or Intel Chip as per your Mac.
3. Extensions:
   - C/C++ by Microsoft
   - Code Runner by Jun Han
   - C/C++ Theme by Microsoft
   - Python 
5. Create a .c file.
6. Go to settings, search "Terminal", Click Run Code..., Check the box: Code Runner: Run in Terminal.
7. Now you can run the .c file.

## Python 
1. Go to: https://www.python.org/downloads/macos/
2. Download latest macOS 64-bit universal2 installer
3. Open Terminal
4. Type `python --version`. If you see the version, it is installed successfully.
5. In VSCode, create demo file and Select Interpreter if needed. (Shift+Cmd+P).

## Git and GitHub
1. Clone a repository: git clone https://github.com/user/repository.git
2. In case you are creating 
3. Check status: `git status`
4. Make changes to files.
5. Stage changes: 
```
git add .                  // add all file changes
git add <file1> <file2>    // add files individually
``` 
6. Commit changes: `git commit -m "Describe your changes"`
7. Push changes: `git push origin main`
8. Pull changes: `git pull origin main`

## ISTF Software Download
1. Go to: https://istf.iitgn.ac.in/software/

## Docker 
1. Go to: https://www.docker.com/get-started/
2. Install whichever fits
3. Open Docker
4. Recommended settings
5. Skip Survey
6. Open Terminal, run `docker --version` to check if successfully installed. 
7. Run: `docker pull hello-world`
8. `docker run hello-world`
9. If it is visible your docker is installed successfully. 
