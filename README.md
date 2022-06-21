# 🌱 Blend2d Scaffold

A minimal blend2d project template

## 🦄 Usage

Simply click the button below to get started:

[![Use this template](https://img.shields.io/badge/use%20this%20template-brightgreen.svg?longCache=true&style=for-the-badge)](https://github.com/xmake-examples/blend2d-scaffold/generate)

## 🔨 Development

###  📋 Requirements

To setup and use the project you will need to have the following tools installed:
 - [Xmake](https://xmake.io/)

###  ⬇️ Installation

Clone the repository

```bash
$ git clone https://github.com/xmake-examples/blend2d-scaffold.git
```

Change the working directory to the newly cloned repository:

```bash
$ cd blend2d-scaffold
```

Run xmake to install the dependencies & build the project:

```bash
$ xmake
note: install or modify (m) these packages (pass -y to skip confirm)?
in xmake-repo:
  -> blend2d 2022.05.12
please input: y (y/n/m)

  => clone https://github.com/blend2d/blend2d.git .. ok
  => install blend2d 2022.05.12 .. ok
[ 25%]: ccache compiling.release src/main.cpp
[ 50%]: linking.release blend2d-scaffold
[100%]: build ok!
```

Run the project after it has been built:

```bash
$ xmake run
```

![](/res/example.png)
