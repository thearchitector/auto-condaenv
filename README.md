# auto-condaenv
A set of patches that enable your shell to automatically switch between project-specific Conda environments. Just place a   `.conda-env` file in the root directory of your project and everything else will be handeled for you.

## Installation
This script simply hooks into the event trigger for changing your current working directory. Run the following commands to append the `cd` hook to your desired shell.

### Fish
```sh
$ curl -L https://git.io/JenWP >> ~/miniconda3/etc/fish/conf.d/conda.fish
```

## License
This work is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License. To view a copy of this license, visit http://creativecommons.org/licenses/by-nc-sa/4.0/ or send a letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.
