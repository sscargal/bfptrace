# bfptrace Scripts and Tips

bpftrace is a high-level tracing language for Linux enhanced Berkeley Packet Filter (eBPF) available in recent Linux kernels (4.x). bpftrace uses LLVM as a backend to compile scripts to BPF-bytecode and makes use of [BCC](https://github.com/iovisor/bcc) for interacting with the Linux BPF system, as well as existing Linux tracing capabilities: kernel dynamic tracing (kprobes), user-level dynamic tracing (uprobes), and tracepoints. The bpftrace language is inspired by awk and C, and predecessor tracers such as DTrace and SystemTap. bpftrace was created by [Alastair Robertson](https://github.com/ajor).

This repository includes my own learning and scripts

# Learn bpftrace
To learn more about bpftrace, see:
- [BPFTrace.org](https://bpftrace.org/)
- [BPFTrace Github README](https://github.com/iovisor/bpftrace/blob/master/README.md)
- [Manual](https://github.com/iovisor/bpftrace/blob/master/man/adoc/bpftrace.adoc) 
- [Reference Guide](https://github.com/iovisor/bpftrace/blob/master/docs/reference_guide.md) 
- [One-Liner Tutorial](https://github.com/iovisor/bpftrace/blob/master/docs/tutorial_one_liners.md)
- [Cheat Sheet](https://www.brendangregg.com/BPF/bpftrace-cheat-sheet.html)
- [Community Forum](https://github.com/iovisor/bpftrace/discussions)
- [Bug Tracker](https://github.com/iovisor/bpftrace/issues)
- [IRC](http://irc.lc/oftc/bpftrace/web@@@)
- [Source Code on Github](https://github.com/iovisor/bpftrace/)
- [bpftrace scripts](https://github.com/iovisor/bpftrace/tree/master/tools)

# Books
<a href="https://www.amazon.com/Systems-Performance-Brendan-Gregg/dp/0136820158?crid=1YIGT6ZGAY93T&keywords=brendan+gregg&qid=1649181818&sprefix=brendan+gregg%2Caps%2C365&sr=8-2&linkCode=li3&tag=stevescarga01-20&linkId=ca8aab42d556bc167da4dfa10083f73e&language=en_US&ref_=as_li_ss_il" target="_blank"><img border="0" src="https://ws-na.amazon-adsystem.com/widgets/q?_encoding=UTF8&ASIN=0136820158&Format=_SL250_&ID=AsinImage&MarketPlace=US&ServiceVersion=20070822&WS=1&tag=stevescarga01-20&language=en_US" ></a><img src="https://ir-na.amazon-adsystem.com/e/ir?t=stevescarga01-20&language=en_US&l=li3&o=1&a=0136820158" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" />  <a href="https://www.amazon.com/Performance-Tools-Addison-Wesley-Professional-Computing/dp/0136554822?crid=1YIGT6ZGAY93T&keywords=brendan+gregg&qid=1649181818&sprefix=brendan+gregg%2Caps%2C365&sr=8-3&linkCode=li3&tag=stevescarga01-20&linkId=548f43c337042d8047c982bec4ad7f6a&language=en_US&ref_=as_li_ss_il" target="_blank"><img border="0" src="https://ws-na.amazon-adsystem.com/widgets/q?_encoding=UTF8&ASIN=0136554822&Format=_SL250_&ID=AsinImage&MarketPlace=US&ServiceVersion=20070822&WS=1&tag=stevescarga01-20&language=en_US" ></a><img src="https://ir-na.amazon-adsystem.com/e/ir?t=stevescarga01-20&language=en_US&l=li3&o=1&a=0136554822" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" />  <a href="https://www.amazon.com/Systems-Performance-Enterprise-Brendan-Gregg/dp/0133390098?crid=1YIGT6ZGAY93T&keywords=brendan+gregg&qid=1649181818&sprefix=brendan+gregg%2Caps%2C365&sr=8-4&linkCode=li3&tag=stevescarga01-20&linkId=1365db938b2bd685328ff5f3057f65dc&language=en_US&ref_=as_li_ss_il" target="_blank"><img border="0" src="https://ws-na.amazon-adsystem.com/widgets/q?_encoding=UTF8&ASIN=0133390098&Format=_SL250_&ID=AsinImage&MarketPlace=US&ServiceVersion=20070822&WS=1&tag=stevescarga01-20&language=en_US" ></a><img src="https://ir-na.amazon-adsystem.com/e/ir?t=stevescarga01-20&language=en_US&l=li3&o=1&a=0133390098" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" /> 
