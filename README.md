# H2Mech
Chemical mechanism of hydrogen V1.0

The chemical mechanism for hydrogen was developed using the Multi-Objective Particle Swarm Method on the GW4 ISAMBARD HPC. Comparisons with existing chemical mechanisms from XJTU [Sun et al., Combust. Flame, 2022] and BHU [Zhu et al., Combust. Flame, 2024] are presented in the table below.

| Objective          | XJTU       | BHU        | Bath       |
|--------------------|------------|------------|------------|
| **nRMSE ALL POINTS** | **0.358** 🔴 | **0.318** 🟠 | **0.234** 🟢 |
| ST                 | 0.747      | 0.492      | 0.407      |
| RCM                | 0.193      | 0.210      | 0.204      |
| LFS                | 0.044      | 0.072      | 0.033      |
| PFR                | 0.450      | 0.498      | 0.291      |
| **Points hit**      | **859/1695** 🔴 | **874/1695** 🟠 | **1023/1695** 🟢 |
| ST point hit       | 114        | 125        | 125        |
| RCM points hit     | 80         | 96         | 96         |
| LFS points hit     | 20         | 19         | 23         |
| PFR points hit     | 645        | 634        | 779        |
