<h1 align="center">
    Large Language Model-Brained GUI Agents: A Survey
</h1>

<div align="center">

[![Agent-Powered](https://img.shields.io/badge/Agent-Powered-0ABAB5?logo=robot-framework&logoColor=white)](https://vyokky.github.io/LLM-Brained-GUI-Agents-Survey/)
[![Paper](https://img.shields.io/badge/Paper-arXiv%3A2411.18279-B31B1B.svg)](https://arxiv.org/abs/2411.18279) 
[![Website](https://img.shields.io/badge/Website-Searchable%20List-blue.svg)](https://vyokky.github.io/LLM-Brained-GUI-Agents-Survey/)
[![github](https://img.shields.io/github/stars/vyokky/LLM-Brained-GUI-Agents-Survey)](https://github.com/vyokky/LLM-Brained-GUI-Agents-Survey)&ensp;

</div>

Welcome to the repository accompanying our survey paper on **Large Language Model-Brained GUI Agents**. This repository contains the code for the searchable paper page and the assets used in the paper. **LLM-Brained GUI Agents** are:

> **Intelligent agents that operate within GUI environments, leveraging Large Language Models (LLMs) as their core inference and cognitive engine to generate, plan, and execute actions in a flexible and adaptive manner.**

## 📖 Read the Paper: [Large Language Model-Brained GUI Agents: A Survey](https://arxiv.org/abs/2411.18279)
<p align="left">
  <img src="assets/gui_agent.png" width="500px"/>
</p>

### 📚 Cite Our Work

If you find our work useful, please consider citing:

```bibtex
@misc{zhang2024largelanguagemodelbrainedgui,
      title={Large Language Model-Brained GUI Agents: A Survey}, 
      author={Chaoyun Zhang and Shilin He and Jiaxu Qian and Bowen Li and Liqun Li and Si Qin and Yu Kang and Minghua Ma and Guyue Liu and Qingwei Lin and Saravan Rajmohan and Dongmei Zhang and Qi Zhang},
      year={2024},
      eprint={2411.18279},
      archivePrefix={arXiv},
      primaryClass={cs.AI},
      url={https://arxiv.org/abs/2411.18279}, 
}
```
---

## 🔍 Explore the **[Searchable Paper Page](https://vyokky.github.io/LLM-Brained-GUI-Agents-Survey/)**

<p align="left">
  <a href="https://vyokky.github.io/LLM-Brained-GUI-Agents-Survey/">
    <img src="assets/webpage.png" width="500px" alt="Webpage Link"/>
  </a>
</p>

The **[Searchable Paper Page](https://vyokky.github.io/LLM-Brained-GUI-Agents-Survey/)** is a web-based interface that allows you to search and filter through the papers in our survey. You can also view the papers by category, platform, and date.


---


## 🙌 Contributing

🤝**Contributions Welcome!**

We encourage the community to contribute to this repository. If you have suggestions for new papers, resources, or improvements, please open an issue or submit a pull request.

To contribute, follow these steps:

1. Find the `*.json` file in the [`data`](https://github.com/vyokky/LLM-Brained-GUI-Agents-Survey/tree/main/webpage/data) directory which matches the category of the paper you want to add. It should be either `survey`, `framework`, `dataset`, `model`, `benchmark`, `gui-testing`, or `visual-assistant`.

    - `survey`: Papers that provide a survey of the LLM-Powered GUI Agents.
    - `framework`: Papers that introduce a new framework or architecture for LLM-Powered GUI Agents.
    - `dataset`: Papers that introduce a new dataset for optimizing models for LLM-Powered GUI Agents.
    - `model`: Papers that introduce a new optimized model for LLM-Powered GUI Agents.
    - `benchmark`: Papers that introduce a new benchmark for evaluating LLM-Powered GUI Agents.
    - `gui-testing`: Papers that uses LLM-powered agents for GUI testing. It is mainly focused on the testing applications aspect.
    - `visual-assistant`: Papers, open-source projects, or products that use LLM-powered agents for visual assistance, such as voice assistants, produtized web agents, etc. It is mainly focused on the applications aspect.

2. In the corresponding json file, add the paper details in the following format to the existing list of papers:

```json
{
    "Name": "Paper Title",
    "Platform": "Device or OS Platform, e.g. Mobile, Web, Desktop, Android, Windows, etc.",
    "Date": "Month Year",
    "Paper_Url": "The paper link of the paper",
    "Highlight": "A brief highlight of the paper, up to 2 sentences.",
    "Code_Url": "The project or code link of the paper",
}
```

---

## 📝 Related Repositories

Here are some other repositories that you might find useful:

- [GUI-Agents-Paper-List](https://github.com/boyugou/GUI-Agents-Paper-List)
- [Awesome-GUI-Agent](https://github.com/showlab/Awesome-GUI-Agent/tree/main)
- [Awesome-LLM-based-Web-Agent-and-Tools](https://github.com/albzni/Awesome-LLM-based-Web-Agent-and-Tools)
- [awesome-ui-agents](https://github.com/opendilab/awesome-ui-agents/)

---

## 🫶 Support Us

⭐ **If you find this repository helpful, please consider to cite our paper and give it a star!**

---

## ❗️ Note
If the authors of the paper wish to have their paper removed from the website, please contact [chaoyun.zhang@microsoft.com](mailto:chaoyun.zhang@microsoft.com).

---
