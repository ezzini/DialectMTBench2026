# **DialectMTBench**: Cross-Dialect Arabic Machine Translation Shared Task

### Hosted with [Arabic Natural Language Processing Conference (ArabicNLP 2026)](https://arabicnlp2026.sigarab.org)

## 1. Overview of the Shared Task
The **Cross-Dialect Arabic Machine Translation Shared Task (DialectMTBench)** focuses on the crucial role of multi-dialectal support in Natural Language Processing (NLP) within the Arab World. The task aims to bridge linguistic gaps in Arabic NLP by including Modern Standard Arabic alongside **ten under-resourced dialects** in the financial domain.

Participants will be provided with innovative parallel corpora to tune and test their machine translation methods. The task evaluates systems' ability to translate text written in one Arabic dialect into another Arabic dialect while preserving meaning, fluency, and dialectal naturalness.

## 2. Motivation and Significance
The rapid growth of Middle Eastern financial markets, digital banking, and fintech ecosystems has increased the need for language technologies that support Arabic users across regional dialects. While formal financial communication is often produced in Modern Standard Arabic, a large portion of user-generated financial discourse — including investor discussions, customer support, and social media commentary — is expressed in local dialects.

This creates a major accessibility challenge, as Arabic dialects can differ substantially in vocabulary, spelling, and expressions across regions. **Effective dialect-to-dialect machine translation** can help bridge communication gaps between speakers of Gulf, Egyptian, Levantine, Maghrebi, and other Arabic varieties.

Key challenges:
- **Linguistic diversity**: Substantial variation across vocabulary, morphology, and spelling between dialects
- **Domain specificity**: Financial language introduces technical terminology and high-stakes meaning distinctions
- **Limited parallel resources**: Most existing MT systems focus on English–Arabic or MSA settings

## 3. Task Description

### Input and Output
- **Input**: A sentence written in a source Arabic dialect (one of 11 varieties: MSA or 10 regional dialects)
- **Output**: A fluent, semantically faithful translation in the specified target dialect

### Supported Dialects
MSA (Modern Standard Arabic), Palestinian, Moroccan, Tunisian, Egyptian, Algerian, Lebanese, Yemeni, Omani, Saudi, Libyan

## 4. Dataset
Participants will utilize an expanded version of the **ArBanking77** dataset:
- **Size**: 3,000 parallel sentences per dialect
- **Domain**: Financial (short user queries — banking intent detection)
- **Annotation**: Translated by native speakers of each dialect
- **Status**: Ready (Train/Dev/Test sets exist)

## 5. Evaluation
- **Primary Metric**: BLEU Score
- **Secondary Metric**: ChrF++
- **Supplementary**: LLM-as-a-judge for fluency and dialectal naturalness

## 6. Baseline System
We have established a baseline system based on **NLLB (No Language Left Behind)**. This baseline, alongside a comprehensive tutorial notebook, will be released on GitHub and Hugging Face.

## 7. Tentative Timeline
- **May 16, 2026**: Release of task website, training/dev data, and evaluation scripts
- **July 20, 2026**: Registration deadline and release of the blind test data
- **July 27, 2026**: End of evaluation cycle (test set submission closes)
- **July 30, 2026**: Final results released
- **August 22, 2026**: System description paper submissions due
- **August 31, 2026**: Notification of acceptance
- **September 1, 2026**: Shared task overview papers due
- **September 10, 2026**: Conference camera-ready deadline
- **October 24–29, 2026**: ArabicNLP 2026 / EMNLP 2026, Budapest, Hungary

## 8. Organizers' Details
- **Saad Ezzini**, King Fahd University of Petroleum and Minerals — saad.ezzini@kfupm.edu.sa
- **Mo El-Haj**, Lancaster University / VinUniversity — elhaj.m@vinuni.edu.vn
- **Mustafa Jarrar**, Hamad Bin Khalifa University — mustafajarrar@gmail.com
- **Samhaa El-Beltagy**, Newgiza University — samhaa@computer.org
- **Mourad Abbas**, High Council of Arabic — m_abbas04@yahoo.fr
- **Fadi Zaraket**, American University of Beirut — fadizaraket@gmail.com
- **Salim Al Mandhari**, Lancaster University — s.m.almandhari@lancaster.ac.uk

## 9. Participation Guidelines
- 📋 **Register here**: [DialectMTBench 2026 Registration Form](https://forms.gle/ETF44zYmTkbL3HBt6)
- For participation guidelines, please refer to [Participation Guidelines](guidelines.md).
- Comprehensive instructions for preparing and submitting your paper(s) are available at [Paper Submission Guidelines](PAPER.md).

---

### Logistics and Support
- **Website Hosting**: GitHub Pages
- **Submission System**: Codabench
- **Code and Tutorials**: GitHub / Hugging Face

### Anti-Harassment Policy
We uphold the [ACL Anti-Harassment Policy](https://www.aclweb.org/adminwiki/index.php?title=Anti-Harassment_Policy), and participants are encouraged to reach out with any concerns to the shared task organizers.
