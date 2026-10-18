# Faiz Sheikh

B.Tech Robotics & AI student at Ramdeobaba University, Nagpur (expected 2028). CGPA 10.0/10 through semester 4.

I work on software, sensor-based prototypes and simulations. Each project below says what works and what doesn't.

## Projects

### [Precision Vault Engine](https://github.com/faiz-sheikh/precision-vault-engine)
A local control layer for LLM provider calls. Every call gets a deterministic fingerprint and passes approval, budget and retry checks before it reaches a provider. Raw responses are checkpointed with hashes, and completed operations are reused instead of repeated.

Work in progress: 157 offline tests pass (1 skipped), no live provider run is demonstrated, and the README lists known limitations.

### [AdaptCAT](https://github.com/faiz-sheikh/adaptcat)
A single-file adaptive assessment prototype with three test products, a 3PL IRT response model, an in-browser technical suite and an optional Supabase backend.

Prototype: item parameters are hand-set, not calibrated, and the admin console and OTP flow are demo-grade.

### [Deep-Learning](https://github.com/faiz-sheikh/Deep-Learning)
Coursework notebooks, from a perceptron and dense networks (MNIST, churn, life expectancy) up to CIFAR-10 CNNs trained from scratch and Beans transfer learning with frozen VGG16 and ResNet50 backbones. Three trained models are on [Hugging Face](https://huggingface.co/faiz4320). Known limitations are listed in the README.

### [Chest-Xray-CNN](https://github.com/faiz-sheikh/Chest-Xray-CNN)
A CNN chest X-ray classification pipeline demo, trained from scratch. The README documents a known data-leakage issue, and the model is not for clinical use. Model card: [Hugging Face](https://huggingface.co/faiz4320/cnn-model).

## Hardware and team projects
No public repositories for these yet.

- **Microplastics detection prototype** (team of 5): laser and photodiode sensing with a digital detected / not-detected output. Working prototype; formal validation pending.
- **Crop Beacon** (team of 2, in development): ESP32-based sensing for farmers, with a basic app prototype.
- **AAKRUTI** (team competition entry): a firefighting reconnaissance robot concept, in the design and simulation stage.

## Stack across these projects
Python, Keras/TensorFlow, scikit-learn, SQLite, Streamlit, JavaScript/HTML (single-file apps), Supabase/PostgreSQL schema, ESP32, SOLIDWORKS Simulation, Git/GitHub, Hugging Face.

## How I work
PVE and AdaptCAT were designed and specified by me and implemented with AI coding assistants. I review the code, run the tests and direct the roadmap. Each README states what is implemented, what isn't, and the known limitations.

<!-- After the CV PDF is added to this repo, uncomment the next line: -->
<!-- [CV (PDF)](Faiz_Sheikh_CV.pdf) -->
