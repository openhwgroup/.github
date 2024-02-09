<img src="https://www.openhwgroup.org/images/openhw-landscape.png" width="418px" height="103px" /> <img src="https://www.openhwgroup.org/images/core-v-portrait.png" align="right" width="150px" height="120px"/>

# About OpenHW Group

OpenHW Group is a not-for-profit, global organization driven by its members and individual contributors where hardware and software designers collaborate in the development of open-source cores, related IP, tools and software. OpenHW provides an infrastructure for hosting high quality open-source HW developments in line with industry best practices.
Please see our [website](https://www.openhwgroup.org/) for membership information, latest news, and further resources.

# OpenHW Group CORE-V Family of Open-Source RISC-V Cores

Below is the CORE-V Roadmap of Application class and Embedded class cores. Please see [core-v-cores repo](https://github.com/openhwgroup/core-v-cores) for roadmap details.
<!-- <img src="https://github.com/openhwgroup/core-v-cores/blob/master/CV-CORES-Roadmap_2023-03-14.png" align="center" /> -->

<img src="https://github.com/openhwgroup/core-v-cores/blob/master/OpenHW-CoresTimeline-Feb2024.png" align="center" />

# Project Repositories Table of Contents 

| Working Group    				| Repo																			| Description												|      
| --------------------    		| --------------------    														| -------------------- 										|
| **Cores TG**    				| [Core-v-cores roadmap](https://github.com/openhwgroup/core-v-cores)			|  															|
|								| [CTG meetings and minutes](https://github.com/openhwgroup/programs/tree/master/TGs/cores-task-group)|							|
| 	*In Active Development* 	| [CVA6](https://github.com/openhwgroup/cva6)									| 6-stage, application-class and embedded-class configurable core family	 	|
|     							| [CVW](https://github.com/openhwgroup/cvw)										| 5-stage, application-class core with education focus |
|     							| [CV32E40PV2](https://github.com/openhwgroup/cv32e40p)							| 4-stage, embedded-class core extending CV32E40Pv1 with FPU and PULP extensions |
|     							| [CV32E40S](https://github.com/openhwgroup/cv32e40s)							| 4-stage, embedded-class core with security focus |
|     							| [CV32E20](https://github.com/openhwgroup/cve2)							    | 2-stage, embedded-class microcontroller core and core complex |
|     							| CV32E40PX	(repo TBD)					    									| 4-stage, embedded-class core extending CV32E40Pv2 with RVB/RVK/RVP and CV-X-IF |
|   *Completed*  				| [CV32E40P](https://github.com/openhwgroup/cv32e40p)							| 4-stage, embedded-class core implementing PULP extensions at TRL5 |
|     							| [CVA5](https://github.com/openhwgroup/cva5)									| 5-stage, FPGA-optimized application-class core at TRL3  |
|     							| [CV32E41P](https://github.com/openhwgroup/cv32e41p)							| 4-stage, embedded-class core prototyping Zfinx and Zce at TRL3 |
|   *Inactive project*  		| [CV32E40X](https://github.com/openhwgroup/cv32e40x)							| 4-stage, embedded-class core supporting X-Interface |
| **Verification TG**    			| [VTG meetings and minutes](https://github.com/openhwgroup/programs/tree/master/TGs/verification-task-group)|   |
|								| [CORE-V Verif](https://github.com/openhwgroup/core-v-verif)					| Common test bench for OpenHW Cores |
|     							| [FORCE RISC-V](https://github.com/openhwgroup/force-riscv)					| Advanced RISC-V instruction set generator |
| **Software TG**     				| [SWTG meetings and minutes](https://github.com/openhwgroup/core-v-sw)			|  												|
| 			    				| [CORE-V GNU Tools](https://github.com/openhwgroup/corev-gcc)					| GNU Tools Project for embedded-class CORE-V cores |
| 			    				| [CORE-V LLVM](https://github.com/openhwgroup/corev-llvm-project)				| LLVM Tools Project for embedded-class CORE-V cores |
| 			    				| [CORE-V FreeRTOS Kernel](https://github.com/openhwgroup/core-v-freertos-kernel)				| FreeRTOS Kernel for embedded-class CORE-V cores |
| 			    				| [CORE-V FreeRTOS](https://github.com/openhwgroup/core-v-freertos)				| FreeRTOS for embedded-class CORE-V cores |
| 			    				| [CORE-V QEMU](https://github.com/openhwgroup/corev-qemu)						| QEMU emulator for CORE-V-MCU	 |
| 			    				| [CORE-V SDK](https://github.com/openhwgroup/core-v-sdk)						| SDK and IDE for 4-stage CORE-V cores	 |
| 			    				| [CVA6 SDK](https://github.com/openhwgroup/cva6-sdk)							| Software tools for the CVA6 core	 |
| **Interconnect TG**				|																				|																	|
|     							| [CV-HPDCACHE](https://github.com/openhwgroup/cv-hpdcache)						| High performance L1 Data Cache |
|     							| [CV-MESH] (repo TBD)															| Coherency framework based on Open Piton |
|     							| [CV-TCCC](https://github.com/openhwgroup/cv-hpdcache)						    | Tightly-coupled cache coherence for CVA6|
|     							| [CORE-V VISION APU] (repo TBD)												| Machine learning SoC including CVA6 and CV-VEC |
|     							| [CVA6-Platform](https://github.com/openhwgroup/cva6-platform)					| Multi-core CVA6 with CV-MESH intended for software testing |
|     							| [CORE-V-POLARA-APU](https://github.com/openhwgroup/core-v-polara-apu)			| Multicore CVA6/CVVEC ASIC with CV-MESH |
|     							| [CORE-V-POLARA-DEVKIT] (repo TBD)												| Development board for Polara APU |
| **Hardware TG**     				| [HWTG meetings and minutes](https://github.com/openhwgroup/programs/tree/master/TGs/hardware-task-group)					|  |
|     							| [CORE-V-MCU](https://github.com/openhwgroup/core-v-mcu)						| ASIC and FPGA MCU implementation of CV32E40P |
|     							| [CORE-V-MCU-DEVKIT](https://github.com/openhwgroup/core-v-mcu-devkit)			| Devkit for CORE-V-MCU |
| **Technical Working Group**	| [OpenHW project dashboard](https://github.com/openhwgroup/programs/tree/master/dashboard)		| |
|								| [Project Description Folders](https://github.com/openhwgroup/programs/tree/master/Project-Descriptions-and-Plans) | |
|								| [OpenHW Project process and templates](https://github.com/openhwgroup/programs/tree/master/process)		| |


<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
