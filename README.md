# decision-time-universality
A small study to observe the universality in Google search query durations. It is used in this paper: [\[1511\.06444\] Universality in halting time and its applications in optimization](https://arxiv.org/abs/1511.06444)

This script makes Google search queries of randomly chosen words and records their durations into a file.

## Usage
- Edit `duration.py` to set the number of words. 
- Run it via `python googledecisionduration.py`
- After it finishes you can plot the graph via `python duration_plot.py`

# References

Results and the definition of universality can be seen in this paper:  

Levent Sagun, Thomas Trogdon, Yann LeCun, [*Universal halting times in optimization and machine learning*](https://arxiv.org/abs/1511.06444) 
