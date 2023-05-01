[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/gotec/git2net-tutorials/HEAD)
[![NBViewer](https://img.shields.io/badge/View%20on-nbviewer-informational)](https://nbviewer.org/github/gotec/git2net-tutorials/tree/main/)

# git2net-tutorials

This repository contains a collection Jupyter notebooks serving as tutorials for `git2net`, an Open Source Python package that facilitates the extraction of co-editing networks from git repositories.

We provide tutorials covering different aspects of analysing your repository with `git2net`.
You can directly interact with the notebooks in *Binder*, or view them in *NBViewer* via the badges at the top.
In addition, we provide links to the individual tutorial notebooks below:

| Tutorial | Binder | Google Colab | NBViewer |
| :---     | :---:    | :---:  | :---: |
| 1. Cloning a repository for analysis | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/gotec/git2net-tutorials/HEAD?labpath=1_Cloning_Git_Repositories.ipynb) | [![Open Cloning Tutorial In Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/gotec/git2net-tutorials/blob/master/1_Cloning_Git_Repositories.ipynb) | [![NBViewer](https://img.shields.io/badge/View%20on-nbviewer-informational)](https://nbviewer.org/github/gotec/git2net-tutorials/tree/main/1_Cloning_Git_Repositories.ipynb) |
| 2. Mining git repositories with [`git2net`](https://github.com/gotec/git2net) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/gotec/git2net-tutorials/HEAD?labpath=2_Mining_Git_Repositories.ipynb) | [![Open Mining Tutorial In Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/gotec/git2net-tutorials/blob/master/2_Mining_Git_Repositories.ipynb) | [![NBViewer](https://img.shields.io/badge/View%20on-nbviewer-informational)](https://nbviewer.org/github/gotec/git2net-tutorials/tree/main/2_Mining_Git_Repositories.ipynb) |
| 3. Author disambiguation with [`gambit`](https://github.com/gotec/gambit) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/gotec/git2net-tutorials/HEAD?labpath=3_Author_Disambiguation.ipynb) | [![Open Disambiguation Tutorial In Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/gotec/git2net-tutorials/blob/master/3_Author_Disambiguation.ipynb) | [![NBViewer](https://img.shields.io/badge/View%20on-nbviewer-informational)](https://nbviewer.org/github/gotec/git2net-tutorials/tree/main/3_Author_Disambiguation.ipynb) |
| 4. Network analysis with [`pathpy`](https://www.pathpy.net/) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/gotec/git2net-tutorials/HEAD?labpath=4_Network_Analysis.ipynb) | [![Open Network Tutorial In Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/gotec/git2net-tutorials/blob/master/4_Network_Analysis.ipynb) | [![NBViewer](https://img.shields.io/badge/View%20on-nbviewer-informational)](https://nbviewer.org/github/gotec/git2net-tutorials/tree/main/4_Network_Analysis.ipynb) |
| 5. Database-based analyses | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/gotec/git2net-tutorials/HEAD?labpath=5_Database_Analysis.ipynb) | [![Open Database Tutorial In Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/gotec/git2net-tutorials/blob/master/5_Database_Analysis.ipynb) | [![NBViewer](https://img.shields.io/badge/View%20on-nbviewer-informational)](https://nbviewer.org/github/gotec/git2net-tutorials/tree/main/5_Database_Analysis.ipynb) |
| 6. Computing file complexity [`git2net`](https://github.com/gotec/git2net) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/gotec/git2net-tutorials/HEAD?labpath=6_Computing_Complexities.ipynb) | [![Open Database Tutorial In Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/gotec/git2net-tutorials/blob/master/6_Computing_Complexities.ipynb) | [![NBViewer](https://img.shields.io/badge/View%20on-nbviewer-informational)](https://nbviewer.org/github/gotec/git2net-tutorials/tree/main/6_Computing_Complexities.ipynb) |

Installation instructions for `git2net` as well as all other information regarding its development can be found in the [original development repository](https://github.com/gotec/git2net).


## git2net @ MSR 2023

You can find the `git2net` tutorial presented at MSR 2023 here:

| Tutorial | Binder | Google Colab | NBViewer |
| :---     | :---:    | :---:  | :---: |
| [`git2net`](https://github.com/gotec/git2net) @ MSR 2023 | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/gotec/git2net-tutorials/HEAD?labpath=MSR_2023.ipynb) | [![Open Database Tutorial In Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/gotec/git2net-tutorials/blob/master/MSR_2023.ipynb) | [![NBViewer](https://img.shields.io/badge/View%20on-nbviewer-informational)](https://nbviewer.org/github/gotec/git2net-tutorials/tree/main/MSR_2023.ipynb) |

## How to cite git2net

``` 
@inproceedings{gote2019git2net,
  title={git2net: {M}ining time-stamped co-editing networks from large git repositories},
  author={Gote, Christoph and Scholtes, Ingo and Schweitzer, Frank},
  booktitle={Proceedings of the 16th International Conference on Mining Software Repositories},
  pages={433--444},
  year={2019},
  organization={IEEE Press}
}

@article{gote2021analysing,
  title={Analysing time-stamped co-editing networks in software development teams using git2net},
  author={Gote, Christoph and Scholtes, Ingo and Schweitzer, Frank},
  journal={Empirical Software Engineering},
  volume={26},
  number={4},
  pages={1--41},
  year={2021},
  publisher={Springer}
}
```


## License

This software is licensed under the GNU Affero General Public License v3 (AGPL-3.0).
