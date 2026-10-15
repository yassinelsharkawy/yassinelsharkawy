# Yassin Elsharkawy

**Cybersecurity Researcher | AI for Cybersecurity | Systems Security**

I work as a security researcher and cybersecurity engineer, with practical experience in security research, and security assessment. My research interests lie at the intersection of cybersecurity, machine learning, and security engineering, particularly in developing interpretable and empirically evaluated methods for security analysis, threat detection, and risk prioritization in real-world systems.

- **Research paper:** [Evaluating Behavioral Context for Interpretable IAM Policy Risk Scoring in Cloud Environments](https://arxiv.org/abs/2610.07345)
- **Security research:** [Security research portfolio and program results](https://hackerone.com/yassinelsharkawy)

## Research and Publication

### Evaluating Behavioral Context for Interpretable IAM Policy Risk Scoring in Cloud Environments

**First author · Peer-reviewed and accepted at an IEEE conference · Conference ID #71863**

[Read the paper on arXiv](https://arxiv.org/abs/2610.07345)

This work examines whether behavioral and environmental signals improve the prioritization of cloud IAM policy risks beyond information contained in policy rules and effective permissions alone. I developed the experimental evaluation pipeline and constructed **AWS-IAM-ContextBench**, a benchmark of 534 AWS experimental observations covering policy, environmental, and behavioral scenarios. The study compares three Explainable Boosting Machine models under leakage-controlled grouped cross-validation, including a full-context model enriched with CloudTrail telemetry. In the reported evaluation, adding behavioral context reduced mean absolute error by 74% and yielded a Spearman rank correlation of 0.973 against reference analyst-priority scores. The conference proceedings have been submitted for inclusion in IEEE Xplore.

## Security Research

I have conducted security research across **43 programs**, with **218+ reports reviewed and accepted by program teams**. My work has included enterprise security programs and public-sector programs involving organizations such as the U.S. Department of Defense, U.S. Department of State, IBM, Amazon, Visa, Beiersdorf, Fiserv, Udemy, Spotify, and the City of Los Angeles Government.

I placed **first worldwide** in the U.S. Department of State security research program and **second worldwide** in the Beiersdorf program. Further details and program testimonials are available on my [security research portfolio](https://hackerone.com/yassinelsharkawy).

My research spans a broad range of vulnerability classes and application security domains, with an emphasis on validating impact, understanding root causes, and communicating practical remediation guidance.

## Selected Projects

### Security Research Labs
[Repository](https://github.com/yassinelsharkawy/labs)

A curriculum of 25 isolated labs across five areas of web security, designed from patterns encountered in practical security research. The labs let learners reproduce vulnerabilities, investigate root causes, switch between vulnerable and patched implementations, and verify whether remediation addresses the underlying defect. I developed the labs to make security research teachable through controlled, practice-based exercises rather than theory alone.

### Efficient Network Intrusion Detection Pipeline
[Repository](https://github.com/yassinelsharkawy/Efficient-Network-Intrusion-Detection-Pipeline)

An end-to-end machine-learning workflow using the CSE-CIC-IDS2018 dataset. It compares a tuned Random Forest baseline with a soft-voting ensemble, documenting preprocessing, feature analysis, model evaluation, and trade-offs among detection rate, false alarms, and training cost.

### LoRA-Based Invoice Information Extraction
[Repository](https://github.com/yassinelsharkawy/LoRA-Adapted-Phi-for-Structured-Information-Extraction-from-Invoices-a-Parameter-Efficient-Approach)

A parameter-efficient fine-tuning experiment using Microsoft Phi-2, LoRA, and 4-bit quantization to transform invoice text into structured JSON. The workflow covers dataset preparation, training and validation splits, tokenization, fine-tuning, and evaluation of generated structured outputs.

### Comparative Analysis of Particle Swarm Optimization Variants for Clustering
[Repository](https://github.com/yassinelsharkawy/Comparative-Analysis-of-Particle-Swarm-Optimization-Variants-for-Clustering)

An interactive framework for comparing six Particle Swarm Optimization variants with a K-Means baseline. The application supports configurable optimization parameters, grid-based parameter search, PCA projections, and complementary evaluation with inertia and silhouette scores, making algorithm behavior easier to inspect under consistent experimental conditions.

### Network Security Toolkit
[Repository](https://github.com/yassinelsharkawy/Network_Security)

A Python toolkit bringing together network scanning, packet sniffing, traffic analysis, ARP-spoofing detection, and related network security utilities. It is intended for authorized assessment and controlled lab environments.

### Windows x64 Native API and CRT-Free Runtime
[Repository](https://github.com/yassinelsharkawy/native-win-runtime)

A C++ systems-engineering project exploring Windows x64 internals, Native API resolution, PE export parsing, assembly-based system-call dispatch, and a freestanding runtime without the standard C runtime. It supports study of low-level execution behavior, reverse engineering, and security-monitoring assumptions.

### PDF JavaScript Behavior and Viewer-Security Testing
[Repository](https://github.com/yassinelsharkawy/PDF-JavaScript-Behavior-and-Viewer-Security-Testing)

A small, reproducible test-artifact generator for examining how PDF viewers handle document-level JavaScript. It compares a benign alert demonstration with a static control and includes structural tests, helping distinguish observed viewer behavior from claims of application-level exploitability.

### Waste Classification Using Computer Vision
[Repository](https://github.com/yassinelsharkawy/ComputerVisionProject)

An image-classification pipeline for waste categorization, organized into preprocessing and augmentation, segmentation, feature extraction, classification, and evaluation. The implementation combines classical image-processing methods with deep feature extraction.

### Deep Learning for Raw-Material Classification
[Repository](https://github.com/yassinelsharkawy/Neural-Networks-Deep-Learning-Project)

An image-classification study combining a ResNet architecture implemented from scratch with transfer learning and fine-tuning using Xception and DenseNet121. The workflow includes image augmentation and evaluation through classification metrics and diagnostic plots.

### Supervised Learning: Digit Recognition and Vehicle CO₂ Prediction
[Repository](https://github.com/yassinelsharkawy/Advanced-Machine-Learning-Supervised-Learning-for-Digit-Recognition-and-Vehicle-CO2-Prediction)

A course project applying decision trees and artificial neural networks to MNIST digit recognition and support vector machines to vehicle CO₂-emissions prediction. It explores classification and regression workflows across image and structured data.

### Multimodal Scientific Paper Summarization

My undergraduate graduation project, completed as team leader under faculty supervision, combined transformer architectures, vision-language models, and retrieval-augmented generation (RAG) for scientific paper summarization. The implementation integrated AI components with Docker-based microservices and cloud infrastructure on Microsoft Azure.

## Teaching and Knowledge Sharing

I volunteered as an instructor in a university student activity, teaching practical security research using labs I designed from my own research experience. The exercises emphasize realistic vulnerability scenarios, reproducible verification, root-cause analysis, and remediation in isolated environments. The [Security Research Labs repository](https://github.com/yassinelsharkawy/labs) documents the curriculum.

## Research Interests

My interests span cybersecurity, privacy, and machine learning, with an emphasis on methods that can be evaluated against realistic systems and clearly defined threat models.

- **AI for cybersecurity:** Interpretable and context-aware security analytics, machine-learning-based intrusion detection, and anomaly detection.
- **AI security and privacy:** Adversarial robustness, trustworthy machine learning, and security and privacy risks associated with model and data use.
- **Privacy-preserving machine learning:** Differential privacy, federated learning, and other privacy-enhancing technologies for data analysis and model development.
- **Cloud and systems security:** Cloud identity and access management (IAM), authorization analysis, least-privilege enforcement, and cloud security telemetry.
- **Software and application security:** Vulnerability discovery, program analysis, secure software design, exploitability assessment, and remediation validation.
- **Network and endpoint security:** Network threat detection, traffic analysis, operating-system internals, reverse engineering, and security monitoring.
- **Privacy engineering and data protection:** Privacy-aware system design, data minimization, access-control mechanisms, and security–privacy trade-offs.
- **Reproducible security research:** Dataset and benchmark construction, controlled experimentation, interpretable evaluation, and validation of defensive measures.

## Contact

For research collaboration, academic opportunities, or technical discussion, please reach me through [LinkedIn](https://linkedin.com/in/yassinelsharkawy).
