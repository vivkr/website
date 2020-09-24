# Structure and Interpretation of Computer Programs 🧙‍♂️

"...the book tells you what [object-oriented programming] principles are, how they came to be selected as worthwhile, how they can be how a different combination of principles might be more appropriate for some quires you to understand the range of possibilities, and to think about rough the design process. Programming is a craft that is subject to frequent failure: many projects are started and abandoned because the designers do not have the flexibility, experience and understanding to come up with a suitable design and implementation. SICP gives you an approach that will succeed, but it is an approach based on principles and wisdom, not on a checklist." - [Peter Norving](https://norvig.com/) on [SICP](https://www.amazon.com/review/R403HR4VL71K8/ref=cm_cr_rdp_perm)

<!-- ### 1. Building Abstractions with Procedures

| | | | | | | | | | |
|-:|-:|-:|-:|-:|-:|-:|-:|-:|-:|
||[1](/sicp/sicp-ex-1-1-solution.html)|[2](SICP/Ex1.2.html)|[3](SICP/Ex1.3.html)|[4](SICP/Ex1.4.html)|[5](SICP/Ex1.5.html)|[6](SICP/Ex1.6.html)|[7](SICP/Ex1.7.html)|[8](SICP/Ex1.8.html)|[9](SICP/Ex1.9.html)|
|[10](SICP/Ex1.10.html)|[11](SICP/Ex1.11.html)|[12](SICP/Ex1.12.html)|[13](SICP/Ex1.13.html)|[14](SICP/Ex1.14.html)|[15](SICP/Ex1.15.html)|[16](SICP/Ex1.16.html)|[17](SICP/Ex1.17.html)|[18](SICP/Ex1.18.html)|[19](SICP/Ex1.19.html)|
|[20](SICP/Ex1.20.html)|[21](SICP/Ex1.21.html)|[22](SICP/Ex1.22.html)|[23](SICP/Ex1.23.html)|[24](SICP/Ex1.24.html)|[25](SICP/Ex1.25.html)|[26](SICP/Ex1.26.html)|[27](SICP/Ex1.27.html)|[28](SICP/Ex1.28.html)|[29](SICP/Ex1.29.html)|
|[30](SICP/Ex1.30.html)|[31](SICP/Ex1.31.html)|[32](SICP/Ex1.32.html)|[33](SICP/Ex1.33.html)|[34](SICP/Ex1.34.html)|[35](SICP/Ex1.35.html)|[36](SICP/Ex1.36.html)|[37](SICP/Ex1.37.html)|[38](SICP/Ex1.38.html)|[39](SICP/Ex1.39.html)|
|[40](SICP/Ex1.40.html)|[41](SICP/Ex1.41.html)|[42](SICP/Ex1.42.html)|[43](SICP/Ex1.43.html)|[44](SICP/Ex1.44.html)|[45](SICP/Ex1.45.html)|[46](SICP/Ex1.46.html)||||

### 2. Building Abstractions with Data

| | | | | | | | | | |
|-:|-:|-:|-:|-:|-:|-:|-:|-:|-:|
||[1](SICP/Ex2.1.html)|[2](SICP/Ex2.2.html)|[3](SICP/Ex2.3.html)|[4](SICP/Ex2.4.html)|[5](SICP/Ex2.5.html)|[6](SICP/Ex2.6.html)|[7](SICP/Ex2.7.html)|[8](SICP/Ex2.8.html)|[9](SICP/Ex2.9.html)|
|[10](SICP/Ex2.10.html)|[11](SICP/Ex2.11.html)|[12](SICP/Ex2.12.html)|[13](SICP/Ex2.13.html)|[14](SICP/Ex2.14.html)|[15](SICP/Ex2.15.html)|[16](SICP/Ex2.16.html)|[17](SICP/Ex2.17.html)|[18](SICP/Ex2.18.html)|[19](SICP/Ex2.19.html)|
|[20](SICP/Ex2.20.html)|[21](SICP/Ex2.21.html)|[22](SICP/Ex2.22.html)|[23](SICP/Ex2.23.html)|[24](SICP/Ex2.24.html)|[25](SICP/Ex2.25.html)|[26](SICP/Ex2.26.html)|[27](SICP/Ex2.27.html)|[28](SICP/Ex2.28.html)|[29](SICP/Ex2.29.html)|
|[30](SICP/Ex2.30.html)|[31](SICP/Ex2.31.html)|[32](SICP/Ex2.32.html)|[33](SICP/Ex2.33.html)|[34](SICP/Ex2.34.html)|[35](SICP/Ex2.35.html)|[36](SICP/Ex2.36.html)|[37](SICP/Ex2.37.html)|[38](SICP/Ex2.38.html)|[39](SICP/Ex2.39.html)|
|[40](SICP/Ex2.40.html)|[41](SICP/Ex2.41.html)|[42](SICP/Ex2.42.html)|[43](SICP/Ex2.43.html)|[44](SICP/Ex2.44.html)|[45](SICP/Ex2.45.html)|[46](SICP/Ex2.46.html)|[47](SICP/Ex2.47.html)|[48](SICP/Ex2.48.html)|[49](SICP/Ex2.49.html)|
|[50](SICP/Ex2.50.html)|[51](SICP/Ex2.51.html)|[52](SICP/Ex2.52.html)|[53](SICP/Ex2.53.html)|[54](SICP/Ex2.54.html)|[55](SICP/Ex2.55.html)|[56](SICP/Ex2.56.html)|[57](SICP/Ex2.57.html)|[58](SICP/Ex2.58.html)|[59](SICP/Ex2.59.html)|
|[60](SICP/Ex2.60.html)|[61](SICP/Ex2.61.html)|[62](SICP/Ex2.62.html)|[63](SICP/Ex2.63.html)|[64](SICP/Ex2.64.html)|[65](SICP/Ex2.65.html)|[66](SICP/Ex2.66.html)|[67](SICP/Ex2.67.html)|[68](SICP/Ex2.68.html)|[69](SICP/Ex2.69.html)|
|[70](SICP/Ex2.70.html)|[71](SICP/Ex2.71.html)|[72](SICP/Ex2.72.html)|[73](SICP/Ex2.73.html)|[74](SICP/Ex2.74.html)|[75](SICP/Ex2.75.html)|[76](SICP/Ex2.76.html)|[77](SICP/Ex2.77.html)|[78](SICP/Ex2.78.html)|[79](SICP/Ex2.79.html)|
|[80](SICP/Ex2.80.html)|[81](SICP/Ex2.81.html)|[82](SICP/Ex2.82.html)|[83](SICP/Ex2.83.html)|[84](SICP/Ex2.84.html)|[85](SICP/Ex2.85.html)|[86](SICP/Ex2.86.html)|[87](SICP/Ex2.87.html)|[88](SICP/Ex2.88.html)|[89](SICP/Ex2.89.html)|
|[90](SICP/Ex2.90.html)|[91](SICP/Ex2.91.html)|[92](SICP/Ex2.92.html)|[93](SICP/Ex2.93.html)|[94](SICP/Ex2.94.html)|[95](SICP/Ex2.95.html)|[96](SICP/Ex2.96.html)|[97](SICP/Ex2.97.html)||| -->