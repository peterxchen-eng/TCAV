## Testing with Concept Activation Vectors (TCAV)
### Interpretability Beyond Feature Attribution: Quantitative Testing with Concept Activation Vectors (TCAV) 
Been Kim, Martin Wattenberg, Justin Gilmer, Carrie Cai, James Wexler, Fernanda Viegas, Rory Sayres

 Paper link: https://arxiv.org/abs/1711.11279

### What is TCAV?

Testing with Concept Activation Vectors (TCAV) is a new interpretability method to understand what signals your neural networks models uses for prediction. 

#### Read my Full Blog Post [here](https://soumyadip1995.blogspot.com/2019/06/tcavs-testing-with-concept-activation.html).

#### Credit goes to this academic Team [here](https://github.com/wso2news/tcav) and [here](https://github.com/fursovia/tcav_nlp)

### What's special about TCAV compared to other methods?

Typical interpretability methods show importance weights in each input feature (e.g, pixel). TCAV instead shows importance of high level concepts (e.g., color, gender, race) for a prediction class -which is how humans communicate!

Typical interpretability methods require you to have one particular image that you are interested in understanding. TCAV gives an explanation that is generally true for a class of interest, beyond one image (global explanation). The key idea is to view the internal state of a neural net as an aid. We will be using CAVs as part of a technique, Testing with CAVs (TCAV), are used to quantify the degree to which a user-defined concept is important to a classification result--for example, how sensitive a prediction of "zebra" is to the presence of stripes. 

For example, for a given class, we can show how much race or gender was important for classifications in  a pretrained model . Even though neither race nor gender labels were part of the training input!

### Why use high level concepts instead of input features?

Humans think and communicate using concepts, and not using numbers (e.g., weights to each feature). When there are lots of numbers to combine and reason about (many features), it becomes harder and harder for humans to make sense of the information they are accounting for. TCAV instead delivers explanations in the way humans communicate to each other.
