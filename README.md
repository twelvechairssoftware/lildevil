# lilDevil
### Cross-platform productivity workstation for developer tools 


#### Prerequisites
 - Qt 5.13+ (https://www.qt.io/download-qt-installer)
 - OSX: cmake and clang compiler
 - Linux: cmake and compatible C++ compiler
 - Windows: Visual Studio 12+ (VS2017)
 
#### Build
Clone this repository

Set appropriate Qt paths in CMakeLists.txt, then:

 - OSX
 
      `cmake -DCMAKE_BUILD_TYPE=MinSizeRel -G "CodeBlocks - Unix Makefiles" <PROJECT_PATH>`
 
      `cmake --build <PROJECT_PATH>/cmake-build-minsizerel --target lilDevil -- -j 2`
 
 - Linux:
 
      `cmake -DCMAKE_BUILD_TYPE=MinSizeRel -G "" <PROJECT_PATH>`
 
      `cmake --build <PROJECT_PATH>/cmake-build-minsizerel --target lilDevil -- -j 2`

 - Windows:
 
      `cmake -DCMAKE_BUILD_TYPE=MinSizeRel -G "" <PROJECT_PATH>`

      `cmake --build <PROJECT_PATH>/cmake-build-minsizerel --target lilDevil -- -j 2`
