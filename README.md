# Reasoning with Neural Cellular Automata

Codebase accompanying the [Reasoning with Neural Cellular Automata](https://arxiv.org/abs/2609.36126v1) paper by the Paradigms of Intelligence team at Google.

## 📓 Notebooks

- **`inference_reproduction.ipynb`**: Runs inference rollouts for trained NCA models on Maze (`Maze-Hard`, `Maze-OOD`) and Sudoku (`Sudoku-Extreme`, `Sudoku-OOD`) benchmarks.
- **`arc_inference_reproduction.ipynb`**: Runs inference rollouts for the pretrained NCA model on ARC-AGI-1, as well as for one evaluation task.
- **`visual_sudoku_reproduction.ipynb`**: Runs inference rollouts for the trained NCA model on Visual-Sudoku.
- **`pruning_reproduction.ipynb`**: Reproduces test-time scaling with niche-capped diversity pruning on a subset of `Sudoku-Extreme`.
- **`training_reproduction.ipynb`**: Runs NCA training from scratch on the `Maze-OOD` benchmark.

## 📜 License

Licensed under the Apache License, Version 2.0. See [LICENSE](LICENSE) for details.

## Reference
If you find our work useful please consider citing
```
@misc{etcheverry2026reasoningneuralcellularautomata,
      title={Reasoning with Neural Cellular Automata}, 
      author={Mayalen Etcheverry and Pietro Miotti and Aidan Sirbu and Konstantin Schürholt and Mariia Drozdova and Arna Ghosh and Blaise Agüera y Arcas and James Manyika and Blake Richards and Eyvind Niklasson},
      year={2026},
      eprint={2609.36126},
      archivePrefix={arXiv},
      primaryClass={cs.LG},
      url={https://arxiv.org/abs/2609.36126}, 
}
```
---

## Disclaimer

This is not an officially supported Google product. This project is not
eligible for the [Google Open Source Software Vulnerability Rewards
Program](https://bughunters.google.com/open-source-security).
