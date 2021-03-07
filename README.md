# Udacity Natural Language Processing Nanodegree

## Machine Translation

Final RNN Model                                                                   |
:--------------------------------------------------------------------------------:|
![](./images/final_rnn_model.png)                                                 |
English (input)                                                                   |
california is busy during september , and it is usually wet in fall .             |
French (label)                                                                    |
californie est occupé en septembre , et il est généralement humide à l' automne . |
Translation (output)                                                              |
californie est occupé en septembre et il est généralement humide à l' automne .   |

This project implements a recurrent neural network that functions as part of an end-to-end machine translation pipeline. It accepts English text as input and returns the French translation.


### Requirements

1. Download and install [Git](https://git-scm.com)
2. Download and install [Anaconda](https://www.anaconda.com)

### Set-up

Clone the project repository
```
git clone https://github.com/sdonatti/nd892-project-machine-translation
```

Install required Python packages
```
cd nd892-project-machine-translation
conda env create -f environment.yaml
conda activate nd892-project-machine-translation
```

Launch the project Jupyter Notebook
```
jupyter notebook machine_translation.ipynb
```

### License

This project is licensed under the [MIT License](LICENSE)