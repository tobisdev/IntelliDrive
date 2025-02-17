# IntelliDrive

IntelliDrive, focuses on developing an artificial driving intelligence in a 2D simulation environment. The simulation encompasses a physically accurate environment in which vehicles autonomously navigate a racetrack. A user-friendly graphical interface allows real-time data visualization and transmission to the neural networks. The implementation focuses on a multi-layer perceptron network optimized using a genetic algorithm.

## Features
- **Generative AI**: Uses advanced AI techniques to learn and adapt driving behavior.
- **Car Customization**: Ability to customize car attributes such as speed, handling, and acceleration.
- **Multiple States**: Includes different states such as MenuState and CarChoosingState for a structured flow.
- **Graphical Interface**: Utilizes SFML for rendering graphics and handling user input.

## Project Statistics

### Contributors:
![Contributors](https://contributors-img.web.app/image?repo=tobisdev/Cpp-GenerativeAI)

### Tools Used:
<p align="left">
  <img src="https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Farrayfire.com%2Flogos%2Farrayfire_logo_whitebkgnd.png&f=1&nofb=1&ipt=492162a18381f8c743d1617b0cdd2ef9776b7e03b649b8cd46e15f8832ee63db&ipo=images" alt="ArrayFire" height="50">
  <img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fraw.githubusercontent.com%2Fdmitriy3342%2Fvs-template-sfml2.5.1-win-ping-pong%2Fmain%2Fdocs%2FSFML_LOGO.png&f=1&nofb=1&ipt=9de402d5957c3ccde66da24cd46b928e0111a22a656fe040d8ebb1cda77b6157&ipo=images" alt="SFML" height="50">
  <img src="https://upload.wikimedia.org/wikipedia/commons/1/18/ISO_C%2B%2B_Logo.svg" alt="C++" height="50">
  <img src="https://upload.wikimedia.org/wikipedia/commons/1/13/Cmake.svg" alt="CMake" height="50">
  <img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fresources.jetbrains.com%2Fstorage%2Fproducts%2Fcompany%2Fbrand%2Flogos%2FCLion_icon.png&f=1&nofb=1&ipt=917eb1a40af6a8bb0bf8cae02279d54e005c2dd5b83774b9a25d5eb49c36c2fe&ipo=images" alt="CLion" height="50">
  <img src="https://upload.wikimedia.org/wikipedia/commons/3/3f/Git_icon.svg" alt="Git" height="50">
  <img src="https://upload.wikimedia.org/wikipedia/commons/9/91/Octicons-mark-github.svg" alt="GitHub" height="50">
  <img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fpluspng.com%2Fimg-png%2Fvisual-studio-logo-png-visual-studio-code-logo-png-transparent-amp-svg-vector-pluspng-2400x2412.png&f=1&nofb=1&ipt=a8f263de14c51eb41fa2005f1d355f0050c031eabf6ea6d0ab999dbda0126725&ipo=images" alt="Visual Studio C++ Compiler" height="50">
</p>

### Code Statistics:
![GitHub top language](https://img.shields.io/github/languages/top/tobisdev/IntelliDrive)
![GitHub language count](https://img.shields.io/github/languages/count/tobisdev/IntelliDrive)
![Lines of code](https://tokei.rs/b1/github/tobisdev/IntelliDrive)

## Images and Videos

### Screenshots from the Game

<div class="image-container">
<img src="/resources/Screenshots/Screen1.png" alt="Screenshot 1" height="150">
<img src="/resources/Screenshots/Screen2.png" alt="Screenshot 2" height="150">
<img src="/resources/Screenshots/Screen3.png" alt="Screenshot 3" height="150">
</div>

### Integration of the AI into our IntelliDrive Project:

<video src="https://github.com/user-attachments/assets/edc46481-7c6f-4be0-9aa9-5d913305f719" width="640" height="360" controls>
Your browser does not support the video tag.
</video>

## Warning

The current code in the **vendors** folder is not originally authored by us, as the CMake configuration still requires modification. Below are the referenced projects:

- [JSON for Modern C++](https://github.com/nlohmann/json)
- [SFML](https://github.com/SFML/SFML)

## Original Repository

Our original repository was [IntelliDrive](https://github.com/voricc/IntelliDrive) but we had to create a new one from a backup because our dependencies got messed up.

## Getting Started

### Prerequisites

- **CLion**: Ensure CLion is installed on your system. [Download CLion](https://www.jetbrains.com/clion/download/)
- **Visual Studio C++ Compiler**: Install the latest version of Visual Studio with C++ development tools. [Download Visual Studio](https://visualstudio.microsoft.com/downloads/)
- **ArrayFire**: Download and install ArrayFire, a high-performance library for parallel computing. [Download ArrayFire](https://arrayfire.com/download)

### Installation
To install and set up this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/tobisdev/Intellidrive.git
    cd IntelliDrive
    ```

2. Build the project using CMake:
    ```bash
    mkdir build
    cd build
    cmake ..
    make
    ```

### Usage
After building the project, you can run the executable to start the AI learning process:

```bash
./bin/IntelliDrive
```

## Contributing
We welcome contributions to the project. Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch with the corresponding name.
3. Make your changes and commit them to your branch.
4. Open a pull request with a detailed description of your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
