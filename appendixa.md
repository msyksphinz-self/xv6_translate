# 付録A. PCハードウェア

本付録では、xv6が動作するプラットフォームであるパーソナルコンピューター(PC)のハードウェアについて説明する。

PCは複数の業界標準に従ったコンピュータであり、その目的は複数のベンダから販売されるPC上でソフトウェアが動作することができるというものである。この標準は、現在のPCと見た目は異なるものの、1990年代のPCから徐々に発展してきたものだ。

PCの外側にはキーボード、画面、そして様々なデバイス(CD-ROMなど)が接続されている。PCの箱の中には回路ボード(マザーボード)、マザーボード上にはCPUチップ、メモリチップ、グラフィックチップ、I/Oコントローラチップ、チップ間を通信するためのバスが接続されている。バスは標準的なプロトコル(PCIやUSBなど)を採用しており、様々なベンダから提供されるPC上で正確に動作するようになっている。

