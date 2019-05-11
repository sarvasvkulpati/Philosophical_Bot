# 🤖 Philosophical Bot 🤖

A Char-RNN network trained on a dataset of philosophical quotes. After reading the works of Nietzsche, Aristotle, Plato, Kant, Descartes, Kierkegaard, and countless others, it seems like it's developed some ideas of its own..... 🤖🤔

This repo is based off of char-rnn-keras by ekzhang. If you want to train your own model compile a dataset as a .txt file and run the training code as shown below.

Also, do download the code and play around with the RNN, some of the quotes it generates are really funny.


## Getting Started

1. Download the project on your computer.
`
git clone https://github.com/sarvasvkulpati/Philosophical_Bot
`
or download the ZIP file

2. Go to the directory with the file: ``` cd Philosophical_Bot ```

3. Generating text:
    - Generate text for model at a certain epoch: ``` python sample.py 100```  
    - Generate text for model at a certain epoch from a seed: ``` python sample.py 100 --seed 'Love is' ``` 


4. Train your own model: ```python train.py --input quotes.txt```

## Some generated quotes

### The meaning of life 🤔

``` The meaning of life is to prevent harm ```

``` The meaning of life is to teach understanding ```

``` The meaning of life is to read ```

### Love is 💕

``` Love is fought to be able to think ```

``` Love is to escape ```

``` Love is a falsehood ```

### Money 🤑

``` Money is freedom ```

``` Money isn't friendship ```

### Random 🔀

``` Do not stoom ```

``` Lome are superiors ```

``` Society, is a church of reason ```

``` Every man is born as mind action ```

``` There is blind, but rather, becomes a worm ```
