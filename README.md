# A little script to simplify repackaging tensorflow into a jupyterlab-enabled container

## Rationale
I needed to recompile Tensorflow because my beloved X5670 doesn't support AVX, and now I need to repackage it into a container with jupyterlab and a couple of fancy modules.

## Usage
`jupiter-lab` -> launches an instance of jupiterlab, /media/shared is mapped on the current dir.
`jupiter-lab --build [WHATSOVER].whl` -> generates a docker image with the specified tensorflow wheel package.

## Note
This thing doesn't cover recompiling Tensorflow, just the container packaging, for that check out https://www.tensorflow.org/install/source

## Disclaimer
I made this script to ease my life in my very specific scenario, if you're a wondering developer who got here searching for "tensorflow + jupyterlab" on github this is very unlikely what you're looking for.
