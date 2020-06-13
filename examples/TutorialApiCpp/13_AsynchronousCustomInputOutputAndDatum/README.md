# Asynchronous Custom Input Output And Datum

## Quick Start

#### 1. Build OpenPose

````dos
> cd <OpenPoseDotNet_dir>
> git submodule update --init --recursive
> cd src\OpenPoseDotNet.Native
> pwsh Build.ps1 <Debug/Release> <cpu/cuda> 64 desktop <2015/2017/2019> <92/100/101>
````

#### 2. Try Tutorial

````dos
> cd <OpenPoseDotNet_dir>\examples\TutorialApiCpp\13_AsynchronousCustomInputOutputAndDatum
> pwsh SymlinkBinary.ps1 <Debug/Release> build_win_desktop_<cpu/cuda>_x64
> dotnet run -c Release -i "examples\media"
````

<img src="images/example_turorial_8.gif"/>