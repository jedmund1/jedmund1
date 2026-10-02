# Hi, I'm Jack Edmunds

I'm a student at Brown University (Class of 2028) studying Computer Science and Applied Mathematics. I'm interested in quantitative finance, software engineering, and data-driven decision making. I like building systems from the ground up and testing them hard.

## Currently

- Software Engineering Intern at Software of America (SWA). I work on a real estate SaaS platform and its shared Go backend.
- NCAA Division I varsity baseball at Brown
- Working on GHOST in Brown's Humans2Robots (H2R) lab
- Directed Reading in Stochastic Modeling & Simulation (APMA)
- Member of Quantitative Trading @ Brown and Brown Investment Group

## Featured Projects

### [Limit Order Book Matching Engine](https://github.com/jedmund1/orderbook-engine) (C++)
- Multi-symbol matching engine with a concurrent bot framework and a market maker that enforces inventory skew and hard risk limits
- Write-ahead log persistence with crash recovery
- 157 tests passing under ASan, UBSan, and TSan
- Replayed against BTC-USD historical data with 0.9867 return correlation
- Includes a React frontend for visualizing order flow and engine state, plus Black-Scholes options pricing
- Built largely with Claude Code. I review and own the correctness of every merged change.

### [Baseball Swing-Timing Analysis](https://github.com/jedmund1/baseball-swing-timing) (Python)
- Pipeline using MediaPipe Pose (pretrained) and librosa audio detection to pull swing-timing features from 300 batting clips
- Cross-referenced with Statcast data through pybaseball, using a self-labeled set of 141 swings
- Found a statistically significant timing difference between whiffs and contact (Mann-Whitney, p = 0.044)

### [Decision Tree Classifier](https://github.com/jedmund1/DecisionTreeML) (Java)
- Supervised learning model built from scratch with no ML libraries
- Recursive tree construction, modular OOP design, and unit tests
- 70 to 85% test accuracy across 4+ datasets

### [Minimax vs. Alpha-Beta Pruning](https://github.com/jedmund1/MinimaxVSAlphaBetaPruning) (Python)
- Side-by-side comparison of minimax search with and without alpha-beta pruning

## Research

### GHOST, Humans2Robots Lab (Brown)
- Working on GHOST, a teleoperation system that enables simultaneous control of two Boston Dynamics Spot robots through Meta Quest VR interfaces
- Advised by Prof. Stefanie Tellex and Prof. James Tompkin

### Stochastic Modeling & Simulation

Brown APMA Directed Reading, Stochastic Modeling & Simulation (Jan 2026 to present):
- Brownian motion simulation in Python from discrete Newtonian dynamics and elastic collisions
- Monte Carlo simulation of 3D particle trajectories to estimate bimolecular reaction rate constants, matching published results (Northrup et al.)

## Technical Skills

- **Languages:** Python (NumPy, Pandas, Matplotlib), C++, Go, C, Java, JavaScript/TypeScript, MATLAB
- **Web:** React/Next.js, Stripe API, MongoDB
- **Infra and tools:** Kubernetes, ArgoCD, Kustomize, GitLab CI/CD, Git, SolidWorks (CAD)
- **AI tooling:** Claude Code and agentic coding workflows, used daily
- **Math:** Probability, Linear Algebra, Differential Equations, Statistical Inference, Stochastic Modeling

## Interests

Quantitative finance and trading, systems and backend engineering, numerical modeling, applied statistics, and sports analytics.

## Contact

- GitHub: [jedmund1](https://github.com/jedmund1)
- LinkedIn: [jack-edmunds](https://www.linkedin.com/in/jack-edmunds)
