
# 📝 Publication
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISLPED 2026</div><img src='images/PALUTE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PALUTE: Processing-In-Memory Acceleration via Lookup Table for Edge LLM Inference](https://arxiv.org/abs/2606.08891) \\
Runyang Tian, Yanru Chen, Weihong Xu, Tajana Rosing.

- Proposed a LUT-based processing-in-memory accelerator using monolithic 3D DRAM for efficient low-bit edge LLM inference.
- Developed an in-DRAM LUT query mechanism and near-memory LUT generator to reduce dequantization, GEMM, nonlinear-operation, and data-movement overheads.
- Achieved 1,264 TPS at 0.16 W, improving energy efficiency by 12.8× over CHIME and 1.6× over FIGLUT, with 2.0× higher area efficiency than PIMPAL under W4A4 inference.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">DATE 2026</div><img src='images/CHIME.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CHIME: Chiplet-based Heterogeneous Near-Memory Acceleration for Edge Multimodal LLM Inference](https://ieeexplore.ieee.org/abstract/document/11539472) \\
Yanru Chen\*, Runyang Tian\*, Yue Pan, Zheyu Li, Weihong Xu, Tajana Rosing.

- Proposed a heterogeneous architecture that integrates M3D DRAM (low-latency, high-endurance) and M3D RRAM (high-density, low-refresh-energy) chiplets.
- Proposed a mapping and scheduling framework for heterogeneous near-memory kernels to fully use the complementary benefits of both memories.
- Improved the energy effciency 246x and speedup 53x compared with Jetson Orin NX. 69.2x higher throughput than the SOTA.
</div>
</div>

- ``DAC 2026`` [HDDB: Efficient In-Storage SQL Database Search Using Hyperdimensional Computing on Ferroelectric NAND Flash](https://arxiv.org/abs/2511.18234)  
Quanling Zhao\*, Yanru Chen\*, Runyang Tian, Sumukh Pinge, Weihong Xu, Augusto Vega, Steven Holmes, Saransh Gupta, Tajana Rosing.
- ``DATE 2026`` [RAPID-Graph: Recursive All-Pairs Shortest Paths Using Processing-in-Memory for Dynamic Programming on Graphs](https://ieeexplore.ieee.org/abstract/document/11539323)  
Yanru Chen\*, Zheyu Li\*, Keming Fan, Runyang Tian, John Hsu, Weihong Xu, Minxuan Zhou, Tajana Rosing.
