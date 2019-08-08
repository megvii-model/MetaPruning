# MetaPruning

This is the pytorch implementation of our paper "MetaPruning: Meta Learning for Automatic Neural Network Channel Pruning", https://arxiv.org/abs/1903.10258, published in ICCV 2019.

Traditional pruning decide prune which channel in each layer and pay human effort in setting the pruning ratio of each layer. MetaPruning automatically search for the best pruning ratio of each layer (i.e., number of channels in each layer). 

MetaPruning contains two steps: 
1. train a meta-net (PruningNet), to provide reliable weights for all the possible combinations of channel numbers in each layer (Pruned Net structures).
2. search for the best Pruned Net by evolutional algorithm and evaluate one best Pruned Net via training it from scratch.

# Citation

If you use the code in your research, please cite:

	@article{liu2019metapruning,
	  title={MetaPruning: Meta Learning for Automatic Neural Network Channel Pruning},
	  author={Liu, Zechun and Mu, Haoyuan and Zhang, Xiangyu and Guo, Zichao and Yang, Xin and Cheng, Tim Kwang-Ting and Sun, Jian},
	  journal={arXiv preprint arXiv:1903.10258},
	  year={2019}
	}


# Code and models

Available on https://github.com/liuzechun/MetaPruning

# Author information

If you have any questions, please do not hesitate to contact Zechun Liu (zliubq@connect.ust.hk).
