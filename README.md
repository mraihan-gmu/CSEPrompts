# CSEPrompts: A Benchmark of Introductory Computer Science Prompts

CSEPrompts is a framework with hundreds of programming exercise prompts and multiple-choice questions from introductory CS and programming courses. It evaluates the performance of LLMs in generating Python code and answering basic CS questions.

---

**Publication**: [International Symposium on Methodologies for Intelligent Systems](https://link.springer.com/book/10.1007/978-3-031-62700-2) 

**Read in [arXiv](https://arxiv.org/pdf/2404.02540)** 

---

## 📝 Citation

If you use this dataset, please cite our paper.

```bibtex
@inproceedings{newman2024cseprompts,
  title={CSEPrompts: A Benchmark of Introductory Computer Science Prompts},
  author={Newman, Christian and Ranasinghe, Tharindu and Zampieri, Marcos},
  booktitle={Foundations of Intelligent Systems: 27th International Symposium, ISMIS 2024, Poitiers, France, June 17--19, 2024, Proceedings},
  pages={45},
  organization={Springer Nature}
}
```



---

## CSEPrompts Benchmark
- **Sources:** Coding websites (e.g., CodingBat, LearnPython) and MOOCs (e.g., Harvard's CS50, UMich's PforE).
- **Statistics:** 118 coding prompts from websites, 101 from MOOCs, and 50 MCQs.
- **Collection:** Manual collection ensuring no duplication.

---


## Research Questions
1. **RQ1:** LLM performance on introductory CS assignments compared to existing benchmarks.
2. **RQ2:** Performance difference on assignments from coding websites vs. academic MOOCs.
3. **RQ3:** LLMs' performance in generating code vs. answering MCQs.
4. **RQ4:** Performance of Code LLMs vs. raw LLMs.

---


### Statistics for Prompts
| Metric             | CodingSites | Academic | MCQ |
|--------------------|-------------|----------|-----|
| Total Prompts      | 118         | 101      | 50  |
| Max. No. of Tokens | 101         | 372      | 221 |
| Min. No. of Tokens | 5           | 17       | 15  |
| Mean No. of Tokens | 28          | 158      | 106 |
| Standard Deviation | 16          | 72       | 51  |

---

### LLMs Used on CSEPrompts
| LLM        | Parameter | Model Type | Reference                                   |
|------------|-----------|------------|---------------------------------------------|
| GPT3.5     | 175B      | Base       | [OpenAI2023GPT4TR](https://arxiv.org/abs/2303.08774) |
| Llama2     | 7B        | Base       | [touvron2023llama](https://arxiv.org/abs/2307.09288) |
| Falcon     | 7B        | Base       | [penedo2023refinedweb](https://arxiv.org/abs/2306.14898) |
| MPT        | 7B        | Base       | [mosaicml_mpt30b](https://arxiv.org/abs/2308.00325) |
| Code-Llama | 7B        | Fine-tuned | [roziere2023code](https://arxiv.org/abs/2308.12950) |
| StarCoder  | 7B        | Fine-tuned | [li2023starcoder](https://arxiv.org/abs/2305.06161) |
| WizardCoder| 7B        | Fine-tuned | [luo2023wizardcoder](https://arxiv.org/abs/2306.08568) |
| Mistral    | 7B        | Base       | [jiang2023mistral](https://arxiv.org/abs/2310.06825) |

---


### Pass@1 Comparison
![Pass@1 Comparison](passat1_comparison.png)

---

### MCQ Performance Comparison
![MCQ Performance Comparison](mcq_performance.png)

---

## References
- [OpenAI2023GPT4TR](https://arxiv.org/abs/2303.08774)
- [touvron2023llama](https://arxiv.org/abs/2307.09288)
- [penedo2023refinedweb](https://arxiv.org/abs/2306.14898)
- [mosaicml_mpt30b](https://arxiv.org/abs/2308.00325)
- [roziere2023code](https://arxiv.org/abs/2308.12950)
- [li2023starcoder](https://arxiv.org/abs/2305.06161)
- [luo2023wizardcoder](https://arxiv.org/abs/2306.08568)
- [jiang2023mistral](https://arxiv.org/abs/2310.06825)

