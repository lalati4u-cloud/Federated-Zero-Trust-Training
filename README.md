# Federated Zero-Trust Training (FZTT)

This repository contains the reference implementation of **Federated Zero-Trust Training (FZTT)**  
and the baseline **FedAvg** experiments for intrusion detection in adversarial federated learning
environments (poisoning and backdoor attacks).

## Documentation
See the `docs/` folder:
- `docs/quickstart.md` – How to run the experiments  
- `docs/fztt.md` – Overview of the FZTT framework  
- `docs/attacks.md` – Poisoning and backdoor attack details  

## Configurations
Human-readable experiment configurations are stored in the `configs/` folder.  
These YAML files document the parameters used in the paper, including:
- Training method (FedAvg / FZTT)  
- Trust parameters  
- Attack setup  

If you use this repository in your research, please cite the code as follows:

```bibtex
@software{FZTT_code,
  author  = {Al-Terkawi, Laila},
  title   = {Federated Zero-Trust Training (FZTT) -- Reference Implementation},
  year    = {2026},
  url     = {https://github.com/<your-username>/<your-repo>},
  note    = {MIT License}
}
