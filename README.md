Quick adapted test on Tensorflow-GPU to be used in [Phoronix-Test-Suites](
https://github.com/phoronix-test-suite/test-profiles).


## Quick Start

* Put this repository in your ${HOME}/.phoronix-test-suite/test-profiles/local/
* Rename the directory to just: __tensorflowgpu__
* With the following commands, to install and run the test:
    * > phoronix-test-suite install tensorflowgpu
    * > phoronix-test-suite run-test tensorflowgpu


## Note 

* Please check the version of your installed CUDA in __install.sh__,
    that must be matched with the tensorflow-gpu.
    Tensorflow-gpu==1.9 requires CUDA==9.0. No less, no more.
