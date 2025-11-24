# DDPG-Based Resource Allocation in MEC-Enabled CR-NOMA Networks  
**Deep Reinforcement Learning for Computation Offloading, Energy Harvesting & Time Sharing Optimization**

This repository contains the complete implementation of our **FYP Thesis**, which was later published at **IEEE WCNC 2024**.  
It models computation offloading for an IoT device in a **MEC + CR-NOMA** environment and optimizes:

- Time-sharing coefficient  
- Energy harvesting duration  
- Transmission duration  
- Overall service delay  

using the **Deep Deterministic Policy Gradient (DDPG)** algorithm.

---

## Key Contributions
- Reinforcement learning agent for dynamic time allocation  
- MEC + CR-NOMA hybrid communication environment  
- Energy harvesting model for secondary IoT devices  
- Deterministic actor–critic learning system  
- Complete simulation pipeline + results  

---

## Repository Structure

research/ → Paper, abstract, citation, and references  
environment/ → MEC, NOMA, channel, and energy harvesting models  
agent/ → DDPG agent, actor/critic networks, replay buffer  
training/ → Training scripts, configs, and loggers  
results/ → Plots, metrics, and evaluation summaries  

---

## Research Paper  
**Optimizing Resource Allocation in MEC-Enabled CR-NOMA-Assisted IoT Networks: A DRL-Driven Strategy**  
*Published at IEEE WCNC 2024 (Wireless Communications and Networking Conference).*

This paper introduces an RL-driven framework where an energy-harvesting IoT device offloads computation to a nearby MEC server using CR-NOMA transmission.  
A Deep Deterministic Policy Gradient (DDPG) agent dynamically allocates time between:

- Data transmission  
- Energy harvesting  
- Local processing  

to **minimize service delay** while maintaining energy sustainability.

### Citation (BibTeX)
```bibtex
@inproceedings{qaiser2024optimizing,
  title={Optimizing Resource Allocation in MEC-Enabled CR-NOMA-Assisted IoT Networks: A DRL-Driven Strategy},
  author={Qaiser, Muhammad Taha and Sohail, Muhammad Sarmad and Shafqat, Minahil and Ullah, Syed Asad and Jung, Haejoon and Hassan, Syed Ali},
  booktitle={2024 IEEE Wireless Communications and Networking Conference (WCNC)},
  pages={1--6},
  year={2024},
  organization={IEEE}
}
