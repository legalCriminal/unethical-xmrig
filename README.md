DOWNLOADING THIS SOFTWARE IS UNHETICAL DONATIONS REMOVED

XMRig is a high performance, open source, cross platform RandomX, KawPow, CryptoNight and [GhostRider](https://github.com/xmrig/xmrig/tree/master/src/crypto/ghostrider#readme) unified CPU/GPU miner and [RandomX benchmark](https://xmrig.com/benchmark). Official binaries are available for Windows, Linux, macOS and FreeBSD.

## Mining backends
- **CPU** (x86/x64/ARMv7/ARMv8)
- **OpenCL** for AMD GPUs.
- **CUDA** for NVIDIA GPUs via external [CUDA plugin](https://github.com/xmrig/xmrig-cuda).

## Download
* **[Binary releases](https://github.com/xmrig/xmrig/releases)**
* **[Build from source](https://xmrig.com/docs/miner/build)**

## Usage
The preferred way to configure the miner is the [JSON config file](https://xmrig.com/docs/miner/config) as it is more flexible and human friendly. The [command line interface](https://xmrig.com/docs/miner/command-line-options) does not cover all features, such as mining profiles for different algorithms. Important options can be changed during runtime without miner restart by editing the config file or executing [API](https://xmrig.com/docs/miner/api) calls.

* **[Wizard](https://xmrig.com/wizard)** helps you create initial configuration for the miner.
* **[Workers](http://workers.xmrig.info)** helps manage your miners via HTTP API.

## Donations
* Default donation 0% (0 minute in 100 minutes) it is disabled in source code.
* give XMR to the creator of the Software if you can (checkout the offical repos at
* **[DONATE]([https://github.com/xmrig/xmrig/](https://github.com/xmrig/xmrig/#donations)
* ) 

## the Developers:
* **[xmrig](https://github.com/xmrig)**
* **[sech1](https://github.com/SChernykh)**
what i know:
  ubuntu build example:
  
  sudo apt-get install git build-essential cmake automake libtool autoconf ;git clone https://github.com/legalCriminal/unethical-xmrig.git ; mkdir unethical/xmrig/build && cd xmrig/scripts ; ./build_deps.sh && cd ../build ; cmake .. -DXMRIG_DEPS=scripts/deps ; make -j$(nproc)
