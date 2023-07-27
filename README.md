# torchFX-cheatsheet
Cheatsheet to manipulate your torch model with [torch.fx](https://pytorch.org/docs/stable/fx.html)

## Why torch.fx cheatsheet
Torch.fx helps developers to conventiently modify the DAG of a model defined in pytorch without diving into the code. As torch.fx has little document and examples, this repo targets to provide some useful examples and tricks for it.



![torch.fx illustration](https://pytorch.org/assets/images/fx-image6.png)


## Contents

* **Modify pytorch computation graph**
  * Add nodes
  * Delete nodes
  * Rename nodes
  * Change output nodes
  * Replace nodes
* **Analyzing pytorch computation graph**
  * Shape propagation
  * Graph spitting
* **Visualize computation graph**
