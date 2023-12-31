# pytorch-analogue

```shell
├── README.md                        <- Top-level README
├── test.ipynb                       <- call all tests
├── modules/                         <- modules implementation
│   ├── __init__.py
│   ├── activations.py
│   ├── base.py
│   ├── criterions.py
│   ├── dataloader.py
│   ├── layers.py
│   └── optimizers.py
└── tests/
    ├── __init__.py
    ├── test_activations.py
    ├── test_base.py
    ├── test_bn.py
    ├── test_criterions.py
    ├── test_dataloader.py
    ├── test_dropout.py
    ├── test_linear.py
    ├── test_optimizers.py
    └── test_sequential.py
```

Simple pytorch reimplementation just for self-education. 

It can be used for training neural networks, all layers and activations can be backpropagated.
