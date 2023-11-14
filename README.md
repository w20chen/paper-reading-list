# Paper Reading List

## Subgraph Matching
1. Shixuan Sun and Qiong Luo. In-Memory Subgraph Matching: An In-depth Study (SIGMOD 2020) [paper](paper/sm_study.pdf)
2. T Jin, B Li, Y Li, Q Zhou, Q Ma, Y Zhao, H Chen, J Cheng. Circinus: Fast Redundancy-Reduced Subgraph Matching (SIGMOD 2023) [paper](paper/sm_circinus.pdf)
3. J Arai, Y Fujiwara, M Onizuka. GuP: Fast Subgraph Matching by Guard-based Pruning (SIGMOD 2023) [paper](paper/sm_gup.pdf)
4. Vincenzo Bonnici, Rosalba Giugno, Alfredo Pulvirenti, Dennis Shasha, Alfredo Ferro. A subgraph isomorphism algorithm and its application to biochemical data (BMC Bioinformatics 2013) [paper](paper/sm_ri.pdf)
5. S Sun, X Sun, Y Che, Q Luo, B He. RapidMatch: A Holistic Approach to Subgraph Query Processing (VLDB 2020) [paper](https://dl.acm.org/doi/10.14778/3425879.3425888)
6. Shixuan Sun, Yulin Che, Lipeng Wang, Qiong Luo. Efficient Parallel Subgraph Enumeration on A Single Machine (ICDE 2019) [paper](https://shixuansun.github.io/files/ICDE19-LIGHT.pdf)

## Approximate Subgraph Matching
1. S Zhang, J Yang, W Jin. SAPPER: Subgraph Indexing and Approximate Matching in Large Graphs (VLDB 2010) [paper](paper/sm_sapper.pdf)
2. Lihui Liu et al. G-Finder: Approximate Attributed Subgraph Matching (IEEE Big Data 2019) [paper](paper/sm_g_finder.pdf)

## Continuous Subgraph Matching
1. Kyoungmin Kim, In Seo, Wook-Shin Han, Jeong-Hoon Lee, Sungpack Hong, Hassan Chafi, Hyungyu Shin, and Geonhwa Jeong. TurboFlux: A Fast Continuous Subgraph Matching System for Streaming Graph Data (SIGMOD 2018) [paper](paper/csm_turboflux.pdf)
2. Shixuan Sun, Xibo Sun, Bingsheng He, Qiong Luo. RapidFlow: An Efficient Approach to Continuous Subgraph Matching (VLDB 2022) [paper](paper/csm_rapidflow.pdf)
3. R Yang, Z Zhang, W Zheng, JX Yu. Fast Continuous Subgraph Matching over Streaming Graphs via Backtracking Reduction (SIGMOD 2023) [paper](paper/csm_calig.pdf)
4. X Sun, S Sun, Q Luo, B He. An In-Depth Study of Continuous Subgraph Matching (VLDB 2022) [paper](paper/csm_study.pdf)
5. S Min, SG Park, K Park, D Giammarresi, GF Italiano, WS Han. Symmetric Continuous Subgraph Matching with Bidirectional Dynamic Programming (VLDB 2021) [paper](paper/symbi.pdf)
6. Sutanay Choudhury, Lawrence B. Holder, George Chin Jr., Khushbu Agarwal, and
John Feo. A Selectivity based approach to Continuous Pattern Detection
in Streaming Graphs. (EDBT 2015) [paper](paper/csm_sjtree.pdf)
7. Wenfei Fan, Jianzhong Li, Jizhou Luo, Zijing Tan, Xin Wang, and Yinghui Wu. Incremental graph pattern matching. (SIGMOD 2011) [paper](paper/csm_incisomat.pdf)
8. Amine Mhedhbi, Chathura Kankanamge, Semih Salihoglu. Optimizing One-time and Continuous Subgraph Queries using Worst-case Optimal Joins [paper](https://dl.acm.org/doi/10.1145/3446980)

## Graph Database
1. X Feng, G Jin, Z Chen, C Liu, S Salihoğlu. KÙZU Graph Database Management System (CIDR 2023) [paper](paper/db_kuzu.pdf)
2. Maciej Besta, Robert Gerstenberger, Marc Fischer, Michał Podstawski, Jürgen Müller, Nils Blach, Berke Egeli, George Mitenkov, Wojciech Chlapek, Marek Michalewicz, Torsten Hoefler. The Graph Database Interface: Scaling Online Transactional and Analytical Graph Workloads to Hundreds of Thousands of Cores (2023) [paper](paper/db_gdi.pdf)
3. Siddhartha Sahu, Amine Mhedhbi, Semih Salihoglu, Jimmy Lin, and M. Tamer Özsu. The Ubiquity of Large Graphs and Surprising Challenges of Graph Processing: Extended Survey (VLDB 2018) [paper](paper/db_ubiquity_of_large_graphs.pdf)
4. Alin Deutsch et al. Graph Pattern Matching in GQL and SQL/PGQ (SIGMOD 2022) [paper](paper/db_gql.pdf)
5. Changji Li, Hongzhi Chen, et al. ByteGraph: A High-Performance Distributed Graph Database in ByteDance (VLDB 2022) [paper](paper/db_bytegraph.pdf)
6. D Olteanu, M Schleich. Factorized databases (SIGMOD 2016)
7. Dan Olteanu, Jakub Závodný. Size Bounds for Factorised Representations of Query Results (ACM Transactions on Database Systems 2015)
8. Amine Mhedhbi, Semih Salihoglu. Optimizing Subgraph Queries by Combining Binary and Worst-Case Optimal Joins (VLDB 2019)
9. Chathura Kankanamge, Siddhartha Sahu, Amine Mhedbhi, Jeremy Chen, and
Semih Salihoglu. Graphflow: An active graph database (SIGMOD 2017) [paper](paper/csm_graphflow.pdf)
10. Christopher R. Aberger, Susan Tu, Kunle Olukotun, Christopher Ré. EmptyHeaded: A Relational Engine for Graph Processing
11. Orri Erling, et al. The LDBC Social Network Benchmark: Interactive Workload
12. Todd L. Veldhuizen. Leapfrog Triejoin: A Simple, Worst-Case Optimal Join Algorithm [paper](https://arxiv.org/abs/1210.0481)
13. Hung Q. Ngo, Christopher Ré, Atri Rudra. Skew Strikes Back: New Developments in the Theory of Join Algorithms (SIGMOD 2013) [paper](https://arxiv.org/abs/1310.3314)

## Other
1. T Akiba, Y Iwata, Y Yoshida. Fast Exact Shortest-Path Distance Queries on Large Networks by Pruned Landmark Labeling (SIGMOD 2013) [paper](paper/o_2_hop_cover.pdf)
2. Hiroshi Inoue, Moriyoshi Ohara, Kenjiro Taura. Faster set intersection with SIMD instructions by reducing branch mispredictions. (VLDB 2014) [paper](paper/o_set_intersection_simd.pdf)
3. Viktor Leis, Peter Boncz, Alfons Kemper, Thomas Neumann. Morsel-Driven Parallelism: A NUMA-Aware Query Evaluation Framework for the Many-Core Age (SIGMOD 2014) [paper](https://15721.courses.cs.cmu.edu/spring2016/papers/p743-leis.pdf)
