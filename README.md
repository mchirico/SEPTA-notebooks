#
SEPTA - Analytics for getting to work

## Setup

For the current setup, I'm using conda python 3.5, since Tensorflow 1.4 doesn't support python 3.6.

```bash
# First install the full version of Anaconda
# https://www.anaconda.com/download/#macos
#
# Next create an environment for just python 3.5
# (I call this psa Python System Analysis)

conda create --name psa python=3.5
source activate psa
pip install -r requirements.txt
```
