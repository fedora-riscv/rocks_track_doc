| package                                            | date             | state    | 备注     |
| -------------------------------------------------- | ---------------- | -------- | -------- |
| uboot-tools-2023.01-2.3.riscv64.fc37               | 2023/2/1 14:14   | complete | 版本领先 |
| gcc-13.0.1-0.1.3.riscv64.fc37                      | 2023/1/30 21:30  | failed   | 版本领先 |
| opensbi-unstable-v1.2.0.2023.01.26.6b5188c-1.fc37  | 2023/1/25 16:38  | complete | 无软件包 |
| opensbi-unstable-v1.2.34.2023.01.25.c45992c-1.fc37 | 2023/1/25 16:38  | complete | 无软件包 |
| libmpc-1.3.1-1.fc38                                | 2023/1/18 16:27  | complete | 版本领先 |
| mpfr-4.1.1-2.fc38                                  | 2023/1/18 15:35  | complete | 版本领先 |
| procps-ng-3.3.17-8.fc38                            | 2023/1/18 14:44  | complete | 版本领先 |
| texinfo-7.0.1-1.fc38                               | 2023/1/18 12:46  | complete | 版本领先 |
| zlib-1.2.13-2.fc38                                 | 2023/1/18 12:01  | complete | 版本领先 |
| make-4.4-1.fc38                                    | 2023/1/18 8:37   | complete | 版本领先 |
| python-rpm-macros-3.11-7.fc38                      | 2023/1/17 11:21  | complete | 版本领先 |
| selinux-policy-38.5-1.fc38                         | 2023/1/17 10:09  | complete | 版本领先 |
| redhat-rpm-config-244-1.0.riscv64.fc38             | 2023/1/17 10:04  | complete | 版本领先 |
| fedora-upgrade-37.2-1.fc38                         | 2023/1/17 9:20   | complete | 编译成功 |
| rust-1.66.1-1.1.riscv64.fc37                       | 2023/1/17 3:16   | complete | 版本领先 |
| marble-22.12.0-1.fc37                              | 2023/1/13 1:10   | complete | 编译成功 |
| libshumate-1.0.3-1.fc37                            | 2023/1/12 23:37  | complete | 编译成功 |
| calindori-22.11-1.fc37                             | 2023/1/12 23:03  | complete | 编译成功 |
| fcitx5-anthy-5.0.13-1.fc37                         | 2023/1/12 22:45  | complete | 编译成功 |
| nemo-5.6.1-1.fc37                                  | 2023/1/12 22:32  | complete | 无软件包 |
| asahi-installer-0.5pre9-1.fc37                     | 2022/11/16 16:09 | complete | 版本领先 |

0307更新：rocks 开始编译 fc38，2023-02-01至03-06 编译13161个，complete 12398个。

| package              | upstream必要性 | source                                                       |
| -------------------- | -------------- | ------------------------------------------------------------ |
| kernel               | Y              | fedora.riscv.rocks:3000/rpms/kernel.git#b6c02a9d00acdd32cacc0703f5f352b50789eda7 |
| libffi               | N              |                                                              |
| execstack            | Y              | fedora.riscv.rocks:3000/rpms/execstack.git#163c366e3f8b77121b819106e36e4d4a2bb4fe8a |
| llhttp               | N              |                                                              |
| libffi3.1            | Y              | fedora.riscv.rocks:3000/rpms/libffi3.1.git#510c20fc9b5611721842794a9856e8fa2712f204 |
| ghc                  | Y              | fedora.riscv.rocks:3000/rpms/ghc.git#a3fdd108ec88aa2fe78bc628364612eb6684df10 |
| ghc-srpm-macros      | N              |                                                              |
| efi-rpm-macros       | Y              | fedora.riscv.rocks:3000/rpms/efi-rpm-macros.git#4b02670d3404ce58d5999e1e6cdc4bb396c0077d |
| kernel-srpm-macros   | N              |                                                              |
| go-rpm-macros        | N              |                                                              |
| openblas-srpm-macros | N              |                                                              |
| rust                 | Y              | fedora.riscv.rocks:3000/rpms/rust.git#ceca7985d2d0b68a51d894e04166328e329bc4fa |
| stb                  | N              |                                                              |
| hdf                  | Y              | fedora.riscv.rocks:3000/rpms/hdf.git#c5c5cb0ad0af7bb8807da82ecfba28fbf256a8ed |
| qt5-qtwebkit         | Y              | fedora.riscv.rocks:3000/rpms/qt5-qtwebkit.git#5584955288f7442e1184fd1d60e6a37a55bbab7b |

