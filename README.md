## Superhero-Name-Generator

Neural network trained on a dataset of 9000 fictional character names, to learn to generate similar names. 

The model predicts the next character for a given input sequence. In order to get a new superhero name, the model needs a seed input (a single character or sequence of characters). The model will then generate the next character. This character is added to the seed input to create a new input, which is then used again to generate the next character, and so on.

### Prerequisites

[Python 3](https://www.python.org/downloads/)

Tensorflow<br/>
`pip install tensorflow`
