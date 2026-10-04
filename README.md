# Feature Collapse


<br>

## Python environment

conda create --name pytorch_env python=3.8 pip -y  
conda activate pytorch_env  
conda install pytorch pytorch-cuda=11.7 -c pytorch -c nvidia  
conda install -c conda-forge scikit-learn -y  
conda install -c conda-forge matplotlib-base -y  
conda install jupyter ipython -y  
jupyter notebook


<br>

## Experiments

Run the repo notebooks to reproduce figure 3, figure 4a, figure 4b and figure 4c of the paper.

## About Feature Learning
Feature learning is a critical mechanism in deep learning, enabling effective generalization. However, a comprehensive understanding of this mechanism remains elusive. We formalize and study a mechanism called "feature collapse" that makes rigorous the idea that local entities s.a. words/patches playing a similar role in a learning task should receive similar representation. We prove for a prototypical NLP task and in the large sample limit that a neural network with a well-designed architecture does exhibit feature collapse. Importantly, our analysis shows that normalization layers s.a. LayerNorm are a key component of this well-designed architecture to achieve feature collapse and generalization, which go hand in hand. Overall, the mathematical investigation shows how good local features can be learned from the global labels of a classification task as long as the network architecture has proper normalization mechanisms.
