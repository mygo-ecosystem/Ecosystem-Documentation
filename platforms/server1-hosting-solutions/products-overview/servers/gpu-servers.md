# GPU Servers

## Local GPU Servers — Overview (Tbilisi, GE)

Deploy high-performance **dedicated GPU servers** in Georgia for AI training/inference, data science, 3D rendering, and video workloads. You get bare-metal performance, full root control, and rapid provisioning.

### Who it’s for

* AI/ML teams running PyTorch or TensorFlow (training, fine-tuning, LoRA, inference)
* Computer vision, multimodal, and NLP pipelines
* Render farms, VFX studios, and real-time encoders (NVENC/NVDEC)
* Data science, HPC batches, and microservice offload for GPU-bound tasks

### Key advantages

* Local low-latency hosting in **Tbilisi, Georgia**
* Dedicated NVIDIA GPUs (no noisy neighbors)
* NVMe storage with RAID options
* Full root/IPMI or iLO access
* 24/7 infrastructure support and fast delivery (up to 3 days)

***

### Plans & Pricing (Monthly)

#### GPU Line (GL) — Dedicated Server · 19-001 — **$366.39 / month**

* CPU: 12 Cores Intel (8 × 3.6 GHz + 4 × 2.7 GHz, 20 threads)
* Memory: 64 GB DDR4 3200 MHz
* Storage: 2 × 2 TB PCIe 4.0 NVMe SSD
* RAID: RAID 0/1 for M.2 NVMe
* GPU: NVIDIA GeForce **RTX 4080** (16 GB GDDR6X)
* Delivery: up to 3 days
* Best for: fine-tuning, mid-batch training, fast FP16/BF16 inference, high-bitrate NVENC.

***

#### GPU Line (GL) — HPE DL380 Gen10 · 19-002 — **$400.31 / month**

* CPU: Intel Xeon Gold 6248 (20 cores, 2.5 GHz)
* Memory: 64 GB DDR4 Registered
* Storage: 2 × 1 TB SATA SSD
* RAID: Smart Array software RAID
* GPU: **NVIDIA RTX 4000 Ada** (20 GB GDDR6)
* Delivery: up to 3 days
* Best for: production inference, CV pipelines, mixed CPU/GPU services with enterprise chassis.

***

#### GPU Line (GL) — HPE DL385 Gen11 · 19-003 — **$1,350.21 / month**

* CPU: AMD EPYC 9335 (32 cores, 3.0 GHz)
* Memory: 128 GB DDR5-6400 Registered
* Storage: 2 × 960 GB NVMe SSD
* RAID: Smart Array software RAID
* NIC: 10/25 GbE × 2 (SFP28)
* GPU: **NVIDIA L40S** (48 GB GDDR6)
* Delivery: up to 3 days
* Best for: larger LLM fine-tunes, diffusion pipelines, heavy vector search, on-GPU embeddings.

***

#### GPU Line (GL) — HPE DL385 Gen11 · 19-004 — **$2,028.71 / month**

* CPU: AMD EPYC 9335 (2 × 32 cores, 64 cores total, 3.0 GHz)
* Memory: 256 GB DDR5-6400 Registered
* Storage: 2 × 3.2 TB NVMe SSD (DWPD 3)
* RAID: Smart Array software RAID
* NIC: 10/25 GbE × 2 (SFP28)
* GPU: **2 × NVIDIA L40S** (total 96 GB GDDR6)
* Delivery: up to 3 days
* Best for: multi-GPU training, larger context inference, parallel render nodes, multi-tenant serving.

***

### What’s included (all GPU servers)

* Dedicated bare-metal host in **Tbilisi, Georgia**
* Full root access; **IPMI/iLO** remote management where applicable
* 1 × IPv4 address (more available on request)
* Redundant power and network; **99.9%** uptime target
* Basic DDoS filtering at edge
* 24/7 infrastructure ticket support (power/network/hardware)

***

### Recommended software stack (on request)

* NVIDIA drivers + CUDA/cuDNN
* Docker + NVIDIA Container Toolkit
* PyTorch / TensorFlow environments
* FFmpeg with NVENC/NVDEC, GStreamer, and GPU codecs
* Triton Inference Server or vLLM/Ollama set-ups

***

### Operating systems

* Ubuntu 24.04 LTS, Ubuntu 22.04 LTS, Debian 12, Proxmox VE 8, Oracle Linux 9, Almalinux 9, Rocky Linux 9
* Windows Server (licensed)
* Custom ISO mounting on request

***

### Storage & RAID notes

* NVMe pairs support **RAID-0** (throughput) or **RAID-1** (mirroring)
* For high write endurance (training checkpoints), we can advise on DWPD-focused SSDs and file systems (XFS/EXT4, ZFS on request)

***

### Networking

* 1 Gbps standard; 10/25 GbE available on select models (see Gen11 builds)
* Private VLANs and cross-rack L2 available on request

***

### Optional add-ons

* Additional IPv4 addresses, private VLAN, dedicated firewall
* Control panels (Plesk/cPanel) for mixed web + GPU workloads
* [**Managed service upgrade**](managed-servers.md) (server hardening, monitoring, patching, incident response, scheduled health checks)

***

### Provisioning & migration

* Typical delivery: **up to 3 days**
* We can preinstall NVIDIA/CUDA/Docker and your base environment
* Free consultative migration for containerized or VM-based stacks

***

### Quick selector

* Real-time inference / rendering with fast cores → **GL 19-001 / 19-002**
* Heavier training / larger embeddings / bigger VRAM → **GL 19-003**
* Multi-GPU training / high-throughput serving → **GL 19-004**

Have questions about batch sizes, VRAM needs, or throughput? Share your framework and model details — we’ll recommend the most cost-effective configuration.

{% embed url="https://console.server1.ge/submitticket.php?deptid=1&language=english&step=2" %}
