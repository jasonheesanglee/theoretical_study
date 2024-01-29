# Theoretical Study

After continuing my studies in the field of AI, I realized that my knowledge needs to be improved to better understand the contents I am dealing with.<br>
Therefore, I decided to study from the very beginning.<br>
Here is the list of the contents I will study.<br>
<sub>The list can be updated and refined as I progress through the studies.</sub>

## Research Paper Implementation

In this directory, Research Paper Implementation will be done.<br>
Here is the order that I completed; the order does not necessarily follow the chronological order of the model development.<br>
I believe the below are the ***MUST*** to learn to start with NLP.<br>
If anyone has any suggestions, please feel free to tell me! :)

- After going through Single Layer Perceptron, I realized that reading a research paper line by line is quite ineffective.<br>Therefore, I have decided to go through only the equations and their explanations and conclusions.


1. Attention Is All You Need (Transformer) ☑️
2. Single Layer Perceptron ☑️
3. Back-Propagation & Multilayer Perceptron ☑️
4. Recurrent Neural Network (RNN) & Long Short-term Memory (LSTM) ☑️
5. Convolutional Neural Network (CNN) <<<< On Going >>>>
6. Gated Recurrent Unit (GRU)
7. Batch Normalization
8. The graph neural network model (GNN)
<p align="center">
  <img alt="image" src="https://github.com/jasonheesanglee/theoretical_study/assets/123557477/cbc40d48-5396-4d59-bd41-1c785a06981f"><br>
  <sub>image retrieved from ResearchGate</sub>
</p>

| Model | Characteristics | Main Weaknesses |
| :---: | :--- | :--- |
| Single-Layer Perceptron |- It is the first Neural Network Model, imitating Human Brain Cell (Neurons) <br>- It is able to solve simple Linear Classification Problems |- Unable to solve XOR problems, which requires more than one classifying standard or Non-Linear Classification.|
| Multi-Layer Perceptron |- It can solve XOR problems with multiple hidden layers.<br>- It is the model where the term "Deep-Learning" came from|- Vanishing & Exploding Gradients<br>- High computation cost for large inputs|
| RNN |- Utilizes hidden states as memory<br>therefore, it is able to process time-series data<br>|- Struggle in long-term dependencies. <br>- The larger data it takes as input, the smaller the inclination the further part gets (due to the multiplication of weights).|
| LSTM |- Solves the long-term dependency problem by applying Cell State (Long-Term memory) and the summation (not multiplication) of the weights<br>- It is designed to mimic the human brain (forgetting unimportant things and remembering important things)|- Too many gates, too much computational cost needed.<br>- Bigger storage (or memory) needed to train longer data, as it is remembering more of the past data than other RNN models.|
| CNN | - | - |
| GRU | - | - |
| Transformer | | |
