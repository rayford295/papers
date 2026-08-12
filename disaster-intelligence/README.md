# Disaster Intelligence / 灾害智能

This directory curates papers on AI-enabled disaster assessment, response, and recovery. The intended scope includes building damage assessment, debris estimation, uncertainty quantification, crowdsourcing and human-AI teaming, multimodal disaster datasets, and rapid post-disaster mapping.

此目录收录 AI 赋能的灾害评估、响应与恢复论文。重点覆盖建筑损毁评估、灾害碎片估计、不确定性量化、众包与人机协同、多模态灾害数据集与快速灾后制图。

## Inclusion Criteria / 收录标准

- Addresses a concrete disaster-cycle problem (preparedness, response, recovery, or mitigation) with stated data and sensing assumptions.
- Treats reliability as a first-class concern: uncertainty, human verification, or decision-relevant evaluation beyond a single accuracy score.
- Connects to the repository's long-term agenda of reliable spatial intelligence under incomplete and changing observations.

## Papers / 论文

### A post-hurricane building debris estimation workflow enabled by uncertainty-aware AI and crowdsourcing (2024)

- **Authors:** Chih-Shen Cheng, Amir Behzadan, Arash Noshadravan
- **Venue:** International Journal of Disaster Risk Reduction, Vol. 112, 104785
- **Paper:** [https://doi.org/10.1016/j.ijdrr.2024.104785](https://doi.org/10.1016/j.ijdrr.2024.104785)
- **Access note:** Closed access (Elsevier); no open-access PDF is legally redistributable, so this entry links to the DOI instead of bundling the file. / 该文为闭源订阅论文，无可合法转载的 PDF，故仅提供 DOI 链接。
- **Core contribution:** A human-AI teaming workflow that estimates post-hurricane building debris volume and composition from aerial imagery, combining uncertainty-aware AI detection and FEMA-based damage classification with a crowdsourcing module that reduces predictive uncertainty (case study: Hurricane Laura).
- **Why it matters here:** Directly relevant to debris-volume estimation pipelines; demonstrates how crowdsourced verification can shrink model uncertainty by up to ~40%, a template for uncertainty-aware post-disaster assessment.
- **Limitations or open question:** Single-event case study; transferability across hurricanes and regions, and integration with conformal or calibrated uncertainty, remain open.

## Entry Template / 条目模板

```markdown
## Paper Title (Year)

- **Authors:**
- **Venue:**
- **Paper:**
- **Code / Data / Project:**
- **Core contribution:**
- **Why it matters here:**
- **Limitations or open question:**
```

See the [English README](../README.md) or [中文 README](../README.zh-CN.md) for the current core reading path.
