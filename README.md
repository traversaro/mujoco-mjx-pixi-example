# mujoco-mjx-pixi-example

Example of running the official Mujoco MJX example without Colab with pixi.

## Requirements

Linux system with Nvidia GPU with CUDA support, with an appropriat amount of VRAM (>4GB fo sure).

## Run

If you do not have it, install [pixi](https://github.com/prefix-dev/pixi#macos-and-linux), then:

~~~
git clone https://github.com/traversaro/mujoco-mjx-pixi-example
cd mujoco-mjx-pixi-example
pixi run tutorial_notebook
~~~

and then follow the notebook.

## Details

The notebook is based on https://github.com/google-deepmind/mujoco/blob/3.0.0/mjx/tutorial.ipynb, with some modifications to permit to run the notebook outside Google Colab.
