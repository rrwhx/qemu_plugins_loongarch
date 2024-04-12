## Get champsim like traces for [Loongarch](https://loongson.github.io/LoongArch-Documentation/LoongArch-Vol1-EN.html)

1. Download QEMU v8.2.2(newest is not supported currently).
2. Patch all patches in patch directory to QEMU
3. compile your QEMU with `mkdir build && cd build/ && ../configure --target-list=loongarch64-linux-user --disable-werror --enable-plugins && ninja`
4. `make -j QEMU_DIR=your_qemu_path`
5. run qemu-loongarch64 with plugins, example in run_simpoint_champsim_trace.sh









