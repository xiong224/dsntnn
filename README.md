# PyTorch DSNT

This repository contains the official implementation of the differentiable
spatial to numerical (DSNT) layer and related operations.

```bash
$ pip install dsntnn
```

## Usage

Please refer to the [basic usage guide](examples/basic_usage.md).

## Scripts

### Running examples

```bash
$ python3 setup.py examples
```

HTML reports will be saved in the `examples/` directory. Please note that the `dsntnn` package must
be installed with `pip install` for the examples to run correctly.

### Running tests

```bash
$ python3 setup.py test     # Run tests
$ python3 setup.py coverage # Run tests with code coverage
```

## Other implementations

* Tensorflow: [ashwhall/dsnt](https://github.com/ashwhall/dsnt)

If you write your own implementation of DSNT, please let me know so that I can add it to
the list. I would also *greatly* appreciate it if you could add the following notice
to your implementation's README:

> Code in this project implements ideas presented in the research paper
> "Numerical Coordinate Regression with Convolutional Neural Networks" by Nibali et al.
> If you use it in your own research project, please be sure to cite the
> original paper appropriately.

## License and citation

(C) 2017 Aiden Nibali

This project is open source under the terms of the
[Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0.html).

If you use any part of this work in a research project, please cite the following paper:

```bibtex
@misc{
  title="Check back here later"
}
```
