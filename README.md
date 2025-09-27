
# Project 1 – Interactive 2D Geometry

This project implements an interactive OpenGL application using SDL3 and GLFW. The user can move, scale, rotate, texture, and animate a shape in real-time.

---

## 📁 Repository Structure

```
Proj1/
├── Header Files/
│   ├── multivector.h
│   ├── pga.h
│   ├── primitives.h
│   └── pga_example.cpp
├── Source Files/
│   ├── glad.c
│   └── squareStarter.cpp
├── brick.ppm
├── goldy.ppm
├── test.ppm
├── glfw3.dll
├── SDL3.dll
├── SDL3_test.dll
└── Linking/
    ├── include/
    │   └── SDL3/
    └── lib/
        └── x64/
```

---

## 🛠️ Visual Studio Setup Instructions

### 1. Configure Project Properties

- **Linker → Input → Additional Dependencies**
  ```
  opengl32.lib
  ```

### 2. Create Linking Folders

Inside your project folder, create:

```
Proj1/Linking/
Proj1/Linking/include/SDL3
Proj1/Linking/lib/x64
```

### 3. Add to Project Settings

#### VC++ Directories

- **Include Directories**:
  ```
  $(ProjectDir)Linking\include
  ```
- **Library Directories**:
  ```
  $(ProjectDir)Linking\lib\x64
  ```

#### C/C++ → General

- **Additional Include Directories**:
  ```
  C:\Users\User\source\repos\Proj1\Linking\include\SDL3
  ```

#### Linker → General

- **Additional Library Directories**:
  ```
  C:\Users\User\source\repos\Proj1\Linking\lib\x64
  ```

#### Linker → Input

- **Additional Dependencies**:
  ```
  GLFW/glfw3.lib
  SDL3.lib
  SDL3_test.lib
  ```

### 4. DLL Placement

Place the following files **next to your .cpp file or executable**:

```
SDL3.dll
glfw3.dll
SDL3_test.dll
```

---

## 🌐 Webpage Link

➡️ [View Project Webpage](https://sh1303.github.io/)  
(Replace with the actual path if it's hosted in a subdirectory)

---

## 💾 Download Executable and Source Code

🔗 [Download ZIP from Google Drive](https://drive.google.com/file/d/1UWvDJEorTjY0S3kJ4tg6lgyUrGI8xihh/view?usp=drive_link)

---

## 📝 Notes

- Make sure all `.lib` and `.dll` files match your system architecture (x64).
- Include all PPM texture files in the same folder as your executable when running.

---

© 2025 Your Name. All rights reserved.
