---
title: "Reading List"
permalink: /miscellaneous/
author_profile: true
redirect_from: 
  - /miscellaneous.html
---
| Category                 | Items                                                                            |
|--------------------------|--------------------------------------------------------------------------------- |
| Computer Architecture | Software optimization resources by Agner [link](http://agner.org/optimize/), [microarchitecture of Intel, AMD and VIA CPUs](http://agner.org/optimize/microarchitecture.pdf). | 
| Computer Architecture | Lectures by Onur Mutlu on Computer Architecture [Youtube videos](https://www.youtube.com/playlist?list=PL5Q2soXY2Zi9OhoVQBXYFIZywZXCPl4M_). |
| Computer Architecture | [Online courses on Computer Architecture by Princeton University](https://www.coursera.org/learn/comparch). |
| Computer Architecture | CPU and performance optimization by [DENIS BAKHVALOV](https://dendibakh.github.io/notes/). [Understanding CPU port contention](https://dendibakh.github.io/blog/2018/03/21/port-contention). [Store forwarding by example.](https://dendibakh.github.io/blog/2018/03/09/Store-forwarding)
| Computer Architecture | Branch predictor [part 1](https://xania.org/201602/bpu-part-one), [part 2](https://xania.org/201602/bpu-part-two) and more on [Micro-architectues](https://xania.org/Microarchitecture) or [code optimization](https://xania.org/).
| Micro-architectural channels | Computer architecture - list of micro-architectural channels, [link](https://github.com/MattPD/cpplinks/blob/master/comparch.micro.channels.md). | 
| Micro-architectural channels | MeltdownPrime and SpectrePrime: Automatically-Synthesized Attacks Exploiting Invalidation-Based Coherence Protocols, [link](https://arxiv.org/abs/1802.03802).|
| Micro-architectural channels | AMD flaws. [link](https://safefirmware.com/amdflaws_whitepaper.pdf), [AMD response](https://community.amd.com/community/amd-corporate/blog/2018/03/20/initial-amd-technical-assessment-of-cts-labs-research) |
| Speculative Execution channels | [Reading privileged memory with a side-channel by Project Zero](https://googleprojectzero.blogspot.ca/2018/01/reading-privileged-memory-with-side.html), [Some thoughts on Spectre and Meltdown](http://www.daemonology.net/blog/2018-01-17-some-thoughts-on-spectre-and-meltdown.html), [Meltdown from a CPU architect's view](https://www.realworldtech.com/forum/?threadid=174129&curpostid=174159). [System Management Mode Speculative Execution Attacks](https://blog.eclypsium.com/2018/05/17/system-management-mode-speculative-execution-attacks/)|
| Speculative Execution channels | [KVA Shadow: mitigating meltdown in Windows](https://blogs.technet.microsoft.com/srd/2018/03/23/kva-shadow-mitigating-meltdown-on-windows/). Speculative Execution Bounty Launch by Microsoft. [link](https://blogs.technet.microsoft.com/msrc/2018/03/14/speculative-execution-bounty-launch/) Microsoft blog on ["Mitigating speculative execution side channel hardware vulnerabilities"](https://blogs.technet.microsoft.com/srd/2018/03/15/mitigating-speculative-execution-side-channel-hardware-vulnerabilities/). |
| Speculative Execution channels | An accessible overview of Meltdown and Spectre: [part 1](https://blog.trailofbits.com/2018/01/30/an-accessible-overview-of-meltdown-and-spectre-part-1/), [part 2](https://blog.trailofbits.com/2018/03/22/an-accessible-overview-of-meltdown-and-spectre-part-2/) |
| Speculative Execution channels on SGX | Intel® Software Guard Extensions (SGX) SW Development Guidance for Potential Bounds Check Bypass (CVE-2017-5753) [Side Channel Exploits](https://software.intel.com/sites/default/files/managed/e1/ec/SGX_SDK_Developer_Guidance-CVE-2017-5753.pdf). [SGXPectre](https://github.com/osusecLab/SgxPectre).
| Intel/AMD technology | Intel SGX Academic Research List, [link](https://software.intel.com/en-us/sgx/academic-research). | 
| Intel/AMD technology | Intel® Architecture Memory Encryption Technologies Specification [pdf](https://software.intel.com/sites/default/files/managed/a5/16/Multi-Key-Total-Memory-Encryption-Spec.pdf). |
| Intel/AMD technology | Intel® MPX explained [pdf](https://intel-mpx.github.io/design/). |
| Secure Enclaves | Open-source Secure Hardware Enclave: [Keystone](https://keystone-enclave.github.io/) |
|Useful tools | External flashing of the firmware. [me_cleaner@github](https://github.com/corna/me_cleaner/wiki/External-flashing). | 
|Useful tools | Cheat sheet for Intel Processor Trace with Linux perf and gdb by Andi Kleen, [link](http://halobates.de/blog/p/410).| 
|Useful tools | [The Basic Toolbox](https://blog.regehr.org/archives/1578) for a computer science students by Prof. John Regehr. | 
| Rowhammer | Nice paper on causing bit flips in Firefox arrays on Android by abusing WebGL shader textures: [here](https://csdl.computer.org/csdl/proceedings/sp/2018/4353/00/435301a357.pdf) | 
| Rowhammer | Codes for Rowhammer attacks. [one-location hammering](https://github.com/IAIK/flipfloyd), [double-sided hammering](https://github.com/IAIK/rowhammerjs/tree/master/native)| 
| Writing and Reviewing papers | How is a paper evaluated? See [here](https://nebelwelt.net/blog/20180303-PCexperience.html). | 
| Writing and Reviewing papers | Reviewing System Security Papers. [link](https://www.sigarch.org/reviewing-system-security-papers/)| 
| Writing and Reviewing papers | Rebuttals: DON'T do [this](https://replicationindex.wordpress.com/2017/11/16/preprint-z-curve-a-method-for-the-estimating-replicability-based-on-test-statistics-in-original-studies-schimmack-brunner-2017/) and try [this](https://www.st.cs.uni-saarland.de/zeller/onresearch/rebuttal-patterns.php3). | 
| Writing and Reviewing papers | Blog: [Paths to External Engagement in Computer Science Research](https://blog.regehr.org/archives/1586) |
| News | [Facebooks cambridge analytica scandal](https://arstechnica.com/tech-policy/2018/03/facebooks-cambridge-analytica-scandal-explained/),  [FTC charged Facebook in 2011](https://www.ftc.gov/news-events/press-releases/2011/11/facebook-settles-ftc-charges-it-deceived-consumers-failing-keep) because it "deceived consumers by telling them they could keep their information on Facebook private and then repeatedly allowing it to be shared and made public". |
| Workshop | [NSF Workshop on Side and Covert Channels in Computing Systems](https://sites.google.com/view/sccs2018/home). Videos: [day 1](https://www.youtube.com/watch?v=DqS5wgN-4Ts), [day 2](https://www.youtube.com/watch?v=U7OeDkoc4RQ) |
