# Introduction to AI

AI is the ability of machines to imitate the cognitive abilities and problem solving capabilities of human intelligence.

Human Intelligence:
- learns new skills through observation
- thinks abstractly and reasons
- communicates using a language nonverbal cues
- handle complex situations in real time
- plans for short and long term
- creates art, music, inventions

If you can replicate any of these human capabilities in machines, this is **Artificial General Intelligence (AGI)**.

When we apply AGI to solve problems with specific and narrow objectives, we call it **Artificial intelligence (AI)**.

AI Examples:
- classifying images
- spam mail classification
- writing computer language code
- predicting old car prices

## Role of AI
    
AI is vital in today's world, and with the amount of data that's generated, **AI far exceeds the human ability to absorb, interpret, and actually make decisions based on that data**.

Why do we need AI ?

1. Automation and Decision Making
    - Approve a credit card loan
    - Process insurance claim
    - Recommend products to customers
    - Detect fraudolent transactions
    - Classify documents and images

2. Creative Support
    - Create content
    - Write stories and poem
    - Provide design
    - Share code
    - Generate ideas
    - Crack jokes

## AI Domains and Examples

![AI Domains and Examples](../images/ai_domains.png)
# Task And Data

![Language-Related AI Tasks](../images/language_ai_tasks.png)

![Speech-Related AI Tasks](../images/speech_ai_tasks.png)

![Vision-Related AI Tasks](../images/vision_ai_tasks.png)# AI vs ML vs DL

AI refers to the broader concept of creating machines or systems that can perform tasks that typically require human intelligence.

ML is a subset of AI that focuses on the development of algorithms that enable machines to learn from and make predictions or decisions based on data. An algorithm refers to a specific set of rules, mathematical equations, or procedures that the machine learning model follows to learn from data and make predictions on.

DL is a subfield of ML that uses **neural networks with many layers** (deep neural networks) to learn and make sense of complex patterns in data.

![AI, ML, DL](../images/ai_ml_dl.png)

## Machine Learning

There are several types of Machine Learning.

- **Supervised Learning** *(extracting rules from data)*
    - the algorithm learns from **labeled data** making predictions or classification
- **Unsupervised learning** *(extracting trends from data)*
    - the algorithm discovers patterns and structures in **unlabeled data** such as clustering or dimensionality reduction
- **Reinforcement Learning** *(solving tasks by trial and error)*
    - the agents learn to make predictions and decisions by interacting with an environment and receiving rewards or punishments

## Supervised Machine Learning

Can we build rules by looking at past data ? We all learn by examples. Past data is nothing but a set of examples.

Through a process of **training**, a model can be built that will have a specific intelligence to do a specific task. The heart of training a model is an **algorithm** that incrementally updates the model by looking at the data samples one by one.

And once it's built, the model can be used to **predict** an outcome on a new data. 

## Unsupervised Machine Learning

Data does not have a specific outcome or a label as we know it. And sometimes, we want to discover **trends** that the data has for potential insights. Similar data can be grouped into **clusters**.

Exploring patterns and data and grouping similar data into clusters drives unsupervised machine learning. 

## Reinforcement Learning

How do we learn to play a game like chess? We'll make a move or a decision, check to see if it's the right move or feedback, and we'll keep the outcomes in your memory for the next step you take, which is learning. 

Reinforcement learning is a machine learning approach where a computer program learns to make decisions by trying different actions and receiving feedback. It teaches agents how to solve tasks by **trial and error**. 

This approach is used in autonomous car driving and robots as well.

## Deep Learning

Deep learning is all about extracting features and rules from data. 

Deep learning is a special kind of machine learning that trains super smart computer networks with lots of layers. These networks can learn things all by themselves from pictures, like figuring out if a picture is a cat or a dog.

## Neural Networks

Neural networks are made up of interconnected nodes or neurons in a layered structure that resembles the human brain. They are an example of a supervised machine learning algorithm that is perhaps the best understood in the context of **functional approximation**. 

Functional approximation involves estimating a hidden function by examining past or currently known data from the specific domain.

![Neural Networks](../images/neural_networks.png)

## Generative AI

Generative AI, is a subset of machine learning that creates diverse content like text, audio, images, and more. These models, often powered by neural networks, learn patterns from existing data to craft fresh and creative output.# Introduction to ML

Machine Learning is a subset of artificial intelligence that focuses on creating computer systems that can learn and improve from experience without being explicitly programmed.

It is powered by algorithms that incorporate intelligence into the machines by automatically learning from the data it consumes.

Machine first learns to identify the objects, and once it succeeds, it can be used to make predictions.

ML application examples:
- online shopping
- movie/video suggestions
- spam mail warning
- self-driving car

## ML Model

In machine learning, the term **model training** is used to build an ML model. During the process of model training, a relationship is established between the input features and output parameters. 

    y = f(x)

Feature **x** are relevant information from the available data selected to train the model. The output label **y** represents the information or prediction that the model aims to generate based on the input features.

The goal is to **approximate the mapping function** so well that when you have new input data x, you can predict the output variable y for that data.

## Data Types

Depending on the type of data, this might have some effect on the type of algorithm that you can use for modeling or the type of questions you can ask of it. 

ML models rely broadly on four primary data types:

- **numeric or quantitative data** (measurable data)

- **categorical data** (characteristics)
    - nominal *(e.g. red, blue, white)*
    - ordinal *(e.g. easy, medium, hard)*

- **time series data** (number sequence)
    - a sequence of numbers collected at regular intervals over a period *(e.g. number of book sales over a year)*

- **text data** (words or paragraphs)

## Flavors of Machine Learning

Machine learning is an **algorithm-driven approach** to create a model. The types of machine learning models depend on whether we have a labeled output or not. 

There are, in general, three types of machine learning approaches:
- supervised
    - used to classify data or make predictions
- unsupervised
    - used to understand relationships within data sets
- reinforcement
    - used to make decisions or choices
    
![ML Examples](../images/ml_examples.png)

## When is ML not the optimal solution ?

While ML provides a good solution for cases where the problem statement is simple and huge labeled data is available, there are places where ML is not a good solution:
- simpler alternatives
- insufficient data
- high costs
- complex data handling
- scalability 

## Standardization in ML

Standardization is the process of transforming data so that it has mean of 0 and a standard deviation of 1. 

It's important in machine learning because it ensures that all features or variables are on the same scale preventing some features from dominating the learning process due to their largest magnitude.

For example, let's say you are building a machine learning model to predict house prices, and you have two features: square footage and number of bedrooms. The square footage values ranges from 1.000 to 5.000 square feet while the number of bedrooms ranges from 1 to 6. So, in case if you don't standardize these features, the model might give more weight to a square footage because it has larger values. And this could result in an inaccurate model as the number of bedrooms might also be a significant predictor. So the standardization scales both those features to have comparable means and standard deviation and hence, allowing the model to treat them equally. # Supervised Learning - Regression

Supervised machine learning is a machine learning model which learns from labeled data. The model learns the mapping between the input and the output. Supervised machine learning is generally used to classify data or make predictions.

Supervised Learning application examples:
- spam detection 
    - output is binary
- disease detection
    - output is binary
- sentiment analysis
    - output is multi-class
- stock price prediction 
    - output is continuous and quantitative

## Example

The inputs to a supervised learning model is the input/output pair. In the figure **x** is the input feature and t is the target. If we want a model to identify fruits, the training inputs would be the features of the fruits, like color, size, and shape, and the output would be the fruit label **t** which can be apple, banana, and so on.

A model is built using these features and the relationship between the features and class labels are established. The training algorithm iteratively trains the models. During training, the model learns the mapping between the input and output. This mapping is the hypothesis. The correctness of the hypothesis is measured, and an error is compared for the training data set. Based on the error, the hypothesis parameters are fine tuned. This loop iteratively continues till the error becomes very small.

The output of the training algorithm is the trained model, which does the prediction. The accuracy of prediction depends on how well the model is trained. The model is trained with a training data set, in this case, various fruits. For instance, if the shape of the object is round and has a depression at the top, and is red in color, then it will be labeled as apple. 

![Supervised Learning Model to Identify Fruits](../images/identify_fruits.png)

## Steps in Supervised Learning

1. **Data Access**

    Labeled data, as per the requirement of the application, is first collected. This data set should represent the problem to be solved.

2. **Data Preparation**

    This is the data pre-processing step, where data is cleaned by removing missing values, outliers, scaling features, and encoding categorical values. The data gets prepared for training.

3. **Modeling**

    In modeling, we split the data as training and testing data. Appropriate machine learning algorithm is selected and applied, as per the requirement. The model is then trained, where the model learns the mapping between the input features and output labels, or values. 
    
4. **Validation**

     Validation helps to identify potential issues, like *overfitting* (when the model memorizes the training data, but fails to generalize well) or *underfitting* (when the model is too simple and cannot capture the underlying patterns in the data).

5. **Deployment**

    Once the model is trained and evaluated, it is deployed and used for prediction.

6. **Monitoring and Iteration**

    Iteratively monitor the model performance and ensure the prediction is accurate with unseen data.

## Types of Supervised Learning

In supervised machine learning, the output can be either:
- categorical (classification problem)
- continuous (regression problem)

![Types of Supervised Learning](../images/supervised_learning.png)

## Regression

Regression is a supervised machine learning technique which is used to predict continuous values based on input data. In contrast to classification, where the goal is to assign data points to discrete classes or categories, regression aims to estimate a continuous output.

Linear regression is the simplest form of regression, where the relationship between the variables is assumed to be linear, represented as a straight line. It aims to find the best-fitting line that **minimizes the sum of squared errors** between the predictor value and the actual target values.

The variable you want to predict is called the dependent variable. The variable you are using to predict the dependent variable's value is called the independent variable. For every data point, the difference between the actual and the predicted value is the loss, or error.

![Regression Line](../images/regression_line.png)

In the example of predicting weight for a given height, based on the existing data points, we can arrive at multiple lines, which can pass through most of the data points. The model picks up the most suitable regression line having the minimum loss. The loss function is called **L2 loss**. It is the square of the difference between a single data point and its predicted value.

Basically, loss is a penalty for a bad prediction. If the model's prediction is perfect, the loss is 0. Otherwise, the loss is high. L2 loss is to be minimized during training throughout the entire data set.

![Regression Loss](../images/regression_loss.png)

Training is a good way to reduce the model's loss, and it is done iteratively. The input features are used to calculate the output label using the relationship represented by the linear regression model. The predicted outputs are compared with the label, and the losses generated. The loss is used in computing the parameter updates. With the computed parameters, the model prediction function is run again. 

![Train a Model](../images/train_a_model.png)

The correctness of the linear model can be evaluated by different evaluation metrics:

- **Mean Absolute Error** is a very simple metric which calculates the absolute difference between the actual and predicted values

- **Mean Squared Error (MSE)** finds the squared difference between the actual and predicted value. The impact of the error is lesser when root mean squared error is used

- **R-squared** evaluates the performance of the model, but not in terms of loss. It is like a threshold matrix, also called **coefficient of determination** or **goodness of fit**. The r value, computed, lies in the range of 0 to 1, where 1 indicates a perfect fit and 0 indicates a worse fit.# Supervised Learning - Classification

Classification is a supervised machine learning technique used to categorize or assign data points into predefined classes or categories based on their features or attributes.

It is used for pattern recognition and predictive modeling. It works with labeled data sets and creates mapping between the input features and the output class labels, and is most suited for binary classification problems.

## Logistic Regression

Logistic regression predicts the output of a categorical dependent variable given the set of independent variables. It gives the output in the form of probabilities between 0 and 1.

Logistic regression uses a **Sigmodal Function** that helps modeling **Binary Classification Problems**. The sigmoidal function, often represented as the sigmoid function, has an S-shaped curve that maps any input value to an output value between 0 and 1.

But why do we need logistic regression instead of linear regression? Linear regression cannot be used to model when there are outliers in the data and the output needs to be in the range 0 to 1.

## Bulding blocks of Evaluation Metrics for Classification

The building blocks of evaluation metrics used in classification is also called **Confusion Matrix**.

![Confusion Matrix Example](../images/confusion_matrix.png)

Based on the four building blocks (true positive, true negative, false positive, false negative), we have three evaluation metrics:

- **accuracy** is the fraction of correct predictions (e.g. it is the ratio of correct predictions to the total number of predictions)

    *For class imbalanced data sets, accuracy alone is not sufficient as we have skewed class proportions. That means one or more classes in the data set may have significantly fewer examples compared to others.*

- **precision** is a measure of how accurately the system identifies positive cases

- **recall** computes the proportion of actual positives which was identified correctly. 

    *Recall helps us understand how well the system captures the positive cases without missing them. A higher recall value indicates that the system is better at identifying the positive cases.*

## Accuracy vs Precision

![Accuracy VS Precision](../images/accuracy_vs_precision.png)# Jupyter Notebooks

**Jupyter Notebook** is a powerful, interactive development environment, which we usually call IDE that allows you to create and share documents containing live code equations, visualizations, and narrative text. It is a very fantastic tool for prototyping data exploration and creating interactive presentations.

## Anaconda

**Anaconda** is an open source distribution of Python and R for Data Science and Machine Learning. It's designed to simplify package management and deployment. It is a toolbox that comes preloaded with all the essential tools and libraries needed for data science and machine learning.

Why to use Anaconda ?

- **Package Management**: easy to install and manage data science libraries and packages
- **Isolated Environments**: you can work on multiple projects with different package versions without any conflicts
- **Anaconda Navigator**: a very user-friendly interface to manage your environments, install packages, and launch Jupyter Notebooks all without needing to use the command line
- **Cross Platform Tool**: it is available for all major operating systems (Windows, Mac, or Linux)

## Machine Learning Process

A typical machine learning process involves:
1. loading data
2. pre-processing
3. training a model
4. evaluating the model
5. making predictions

## Pythons Libraries

**Pandas Library** is used for data manipulation and provides data structures like dataframes and series for handling data efficiently.

**Scikit Learn** (sklearn) is a popular machine learning library that provides tool for data pre-processing, model training, and evaluation. 

**NumPy** library is used for numerical computations and provides arrays and mathematical functions.

## How to install libraries with Anaconda

    conda install -c anaconda scikit-learn
    conda install -c anaconda numpy# Unsupervised Learning

Unsupervised machine learning is a type of machine learning where there are no labeled outputs. The algorithm learns the patterns and relationships in the data and groups similar data items. In unsupervised machine learning, the patterns in the data are explored explicitly without being told what to look.

## Clustering

Clustering is a method of grouping data items based on similarities. Within a cluster, the data items are more similar than the items outside the cluster. If some data items do not fall within any cluster, these data items are deemed as **outlier points**.

Similarity is how close two data points are to each other and is a value between 0 and 1. Similarity between objects decide which cluster they will fall into, and hence, important for clustering. 

Partition-based clustering algorithms are used to divide data points into nonoverlapping clusters, where each data point belongs to exactly one cluster. The most well-known example of a partition-based clustering algorithm is **K-Means**. K-Means iteratively assigns data points to the nearest cluster center and then recomputes cluster centers until convergence, resulting in distinct, nonoverlapping clusters.

![Clustering](../images/clustering.png)

## Unsupervised Workflow

1. Prepare the data
2. Create similarity metrics
3. Run clustering algorythm
4. Interpret results and adjust clustering

![Unsupervised Workflow](../images/unsupervised_workflow.png)

 ## Use Cases

- Market segmentation
- Outlier Analysis
- Recommendation Systems

# Reinforcement Learning

**Reinforcement Learning** is a type of Machine Learning that enables an agent to learn from its interaction with the environment, while receiving feedback in the form of rewards or penalties without any labeled data.

*Reinforcement Learning is like teaching a dog new tricks: you reward it when it does something right, and over time, it learns to perform these actions to get more rewards.*

## Use Cases

- Autonomous vehicles
- Smart devices
- Industrial automation
- Gaming and entertainment

## Terminology in RL

1. **Agent**: interacts with environment, takes actions, learns from feedback

2. **Environment**: external system with which the agent interacts

3. **State**: representation of the current situation of the environment at a particular time 

4. **Action**: possible moves or decisions that the agent can take in each state

5. **Policy**: mapping that the agent uses to decide which action to take in a given state

The goal of reinforcement learning algorithm is to find a policy that will yield a lot of rewards for the agent if the agent follows that policy referred to as the optimal policy.

Through a process of learning from experiences and feedback, the agent becomes more proficient at making good decisions and accomplishing tasks. This process continues until eventually we end up with the optimal policy. The optimal policy is learned through training by using algorithms like **Deep Q Learning** or **Q Learning**.

![Train a Robotic Arm Using RL](../images/robotic_arm.png)# Introduction to DL

Deep Learning is a subset of machine learning that focuses on training Artificial Neural Networks (ANNs) to solve a task at hand. 

A very important quality of the ANN is that it can process raw data like pixels of an image and extract patterns from it. These patterns are treated as features to predict the outcomes.

ANN accepts image pixels as inputs, extract patterns like edges and curves and so on, and correlates these patterns to predict an outcome. 

## Why do we need Deep Learning

1. ML needs us to specify features
2. DL extracts features from raw and complex data
3. Internal representation of data is built using extracted features (this may not be feasible manually!)
4. DL algorithms can make use of parallel computations (data is split into small batches and process parallelly)
5. This leads to scalability and performance

In short, Deep Learning complements machine learning algorithms for complex data for which features cannot be described easily.

![ANNs](../images/anns.png)

## History of DL

![History of DL](../images/history_dl.png)

## Types of DL 

![Types of DL](../images/types_dl.png)

![DL Algorithms](../images/dl_algorithms.png)

## Artificial Neural Networks (ANNs)

Artificial Neural Networks (ANNs) are inspired by the human brain. They are made up of interconnected nodes called as neurons.

In ANN, we assign weights to the connection between neurons. Weighted inputs are added up. If the sum crosses a specified threshold, the neuron is fired and the outputs of a layer of neuron become an input to an another layer.

ANN Building Blocks:

- **Layers**: input, hidden, output layers receive inputs, transform it, and produce outputx
- **Neurons**: computational units which accepts an input and produce an output
- **Weights**: determines the strength of connection between neurons (the connection could be between input and a neuron, or it could be between a neuron and another neuron)
- **Activation Function**: works on weighted sum of inputs to a neuron and produces an output
- **Bias**: additional input to a neuron that allows certain degree of flexibility

*Hidden layers in neural networks are crucial for character recognition because they enable the network to learn and extract complex features and patterns, such as edges, shapes, and curves, which are essential for recognizing characters.*

*A neuron in an Artificial Neural Network is the fundamental building block responsible for performing weighted summation and applying an activation function to input data to produce an output.*

![ANN Building Blocks](../images/ann_blocks.png)

![ANN Example](../images/ann_example.png)

## How are ANNs trained ?

During training, we show an image to the ANN. Let us say it is an image of digit 2. So we expect output neuron for digit 2 to fire. But in real, let us say output neuron of a digit 6 fired. So what do we do? We know that there is an error. So to correct an error, we adjust the weights of the connection between neurons based on a calculation, which we call as **Backpropagation Algorithm**. By showing thousands of images and adjusting the weights iteratively, ANN is able to predict correct outcome for most of the input images. 

This process of adjusting weights through backpropagation is called as **model training**. 

Backpropagation Algorithm:

1. Guess and compare
2. Measure the error
3. Adjust the guess
4. Update the weight
# Deep Learning Models

Deep Learning Model Architectures:

- **Feed Forward Neural Networks (FNNs)**:  they are the simplest form of neural networks, also called as Multi Layer Perceptron (MLP).

- **Convolutional Neural Networks (CNNs)**: they can automatically detect and learn local patterns and features in images and videos.

- **Recurrent Neural Network (RNNs)**: they are designed to handle sequential data, such as time series data or natural language. They have a feedback loop that allows them to maintain hidden states and capture temporal dependencies.

- **Autoencoders**: they are unsupervised learning models used for feature extraction and dimensionality reduction, and is commonly employed in data compression and anomaly detection.

- **Long Short Term Memory (LSTM)**: it is a specialized RNN variant designed to handle long term dependencies in sequential data.

- **Generative Adversarial Network (GAN)**: it is used for generating realistic synthetic data, such as images, audio, and text.

- **Transformers**: they are widely used in natural language processing and have become state of the art models for tasks, like machine translation, text generation, and language understanding.
# DL Models - Sequence Models

Sequence Models are used to solve problems where the input data is in the form of sequences. The sequences are ordered lists of data points or events.

The goal in sequence models is to find patterns and dependencies within the data and make predictions, classifications, or even generate new sequences.

Common examples of the sequence models:
- Natural Language Processing
    - Machine translation
    - Sentiment analysis
    - Text generation
- Speech Recognition
    - Convert a recorded audio into text
- Music Generation
    - Generate new music or create original compositions
- Gesture Recognition
    - Sign language recognition
- Time Series Analysis
    - Predict future values

*Sequence models are indeed well-suited for tasks involving sequentially ordered data points or events, such as time series analysis, natural language processing, speech recognition, and language translation. However, for image classification and object recognition, traditional machine learning models and convolutional neural networks (CNNs) are more commonly used.*

## Recurrent Neural Networks (RNNs)

Recurrent Neural Networks (RNNs) are a class of neural network architectures specifically designed to handle sequential data. Unlike traditional feedforward neural network, RNNs have a **feedback loop** that allows information to persist across different timesteps. 

The key features of RNN is their ability to maintain an internal state often referred to as a **hidden state** or **memory**, which is updated as the network processes each element in the input sequence. 

The hidden state is then used as input to the network for the next time step, allowing the model to capture dependencies and patterns in the data that are spread across time. 

Types of RNNs:
1. **One-to-One**: Standard non-sequential data like FeedForward Neural Network (FNN)
2. **One-to-Many**: Produces multiple output values for one input values (e.g. music generation)
3. **Many-to-One**: Produces one output values for multiple input values (e.g. sentiment analysis)
4. **Many-to-Many**: Produces multiple ouput values for multiple input values (e.g. machine translation, named entity recognition)

RNN does not perform that well when it comes to capturing long term dependencies. This is due to the vanishing gradients problem, which is overcome by using LSTM model. 

*Machine Translation involves translating a sentence or a sequence of text from one language to another, which is essentially a sequence-to-sequence problem. In the Many-to-Many RNN architecture, the network takes a sequence of inputs and produces a sequence of outputs. In the context of machine translation, this means it can take a sequence of words or tokens in one language as input and generate a corresponding sequence of words or tokens in another language as output.*

## Long Short-Term Memory (LSTM) 

Long Short-Term Memory (LSTM), works by using a specialized memory cell and a gating mechanisms to capture long term dependencies in the sequential data.

The key idea behind LSTM is to selectively remember or forget information over time, enabling the model to maintain relevant information over long sequences, which helps overcome the vanishing gradients problem.

The core of the LSTM lies in its **gating mechanisms**, which include three gates:
- the input gate
- the forget gate
- the output gate. 

These gates are like the filters that control the flow of information within the LSTM cell.

*Long Short-Term Memory (LSTM) Neural Networks are the sequence model of choice when it comes to handling and maintaining relevant information over long sequences, making them particularly well-suited for tasks such as language modeling, machine translation, and speech recognition.*

![LSTM](../images/lstm.png)# DL Models - Convolutional Neural Networks

Convolutional Neural Network (CNN) is a type of deep learning model specifically designed for processing and analyzing **grid-like data**, such as images and videos. 

The role of the CNN is to reduce the image into a form, which is easier to process and without losing features, which are critical for getting a good prediction.

![Convolutional Neural Networks](../images/cnn.png)

*In the ANN for handwritten characted recognition the input image is converted to a single dimensional array and given as an input to the network. But that does not work well with the image data because image data is inherently two dimensional. CNN works better with two dimensional data.*

## Limitations of CNN

CNNs do have some limitations:
- Computation: require massive data and computations
- Overfitting: happens with limited training data
- Interpretability: typical black-box model
- Sensitivity: highly sensitive to input variations

## Applications of CNN

- Image Classification
- Object Detection
    - The goal here is to draw bounding boxes around objects in an image.
- Image Segmentation
- Face Recognition
- Medical Imaging
- Autonomous Vehicles
- Remote Sensing
# Introduction to Generative AI

Generative AI refers to a type of AI that can create new content. It is a subset of Deep Learning, where the models are trained not to make predictions but rather to generate output on their own.

Generative models can create a wide range of outputs, such as images, music, speech, text, or other types of data.

Think of Generative AI as an artist who looks at a lot of paintings and learns the patterns and styles present in them. Once it has learned these patterns, it can generate new paintings that resembles what it learned.

It is important to note that generative models are not truly creative or understanding humans as they rely on patterns in the data they were trained on and don't have emotions or personal experiences.

*Generative AI is focused on creating new content or data rather than making predictions based on existing training data. It involves generating novel and meaningful outputs such as images, text, music, or other forms of creative content.*

![Generative AI](../images/generative_ai.png)

## How does generative AI works ?

To explain this in a simple way, let's imagine you are trying to teach a generative AI model to draw a dog.

You would start by giving it a lot of pictures of dogs to learn from. The AI does not know anything about what a dog looks like. But by looking at these pictures, it starts to figure out common patterns and features, like dogs often have pointy ears, narrow faces, whiskers, et cetera. You can then ask it to draw a new picture of a dog.

The AI will use the patterns it learned to generate a picture that hopefully looks like a dog. But remember, the AI is not copying any of the pictures it has seen before but creating a new image based on the patterns it has learned. In practice the process involves a lot of complex maths and computation. 

There are different techniques and architectures that can be used, such as:
- Variational Autoencoders (VAs)
- Generative Adversarial Networks (GANs)

## Generative AI is different from other AI approaches

AI approaches like supervised learning or reinforcement learning are typically used for tasks, like classification, recommendation systems, and game playing, where focus is on decision making and optimization.

Generative AI model aims to understand the structure of data and learn how to generate similar samples.

![Generative AI Model](../images/generative_ai_model.png)

## Types of Generative AI Models
- Image-Based
    - Generates visual contents
    - learn from large collections of image data
- Text-Based
    - Generates textual contents
    - Learns from large collections of text data

## Generative Adversarial Data (GAN)

Generative Adversarial Network (GAN) is widely used for image generation tasks.

## Transformers and Large Language Models (LLM)

Transformers and Large Language Models (LLM) are very good example for a text based generative model. 

They are built to understand generate and process human language at a massive scale. These models are typically based on deep learning architectures, such as transformers, and are trained on vast amount of text data to learn language patterns and relationships.

## Generative AI Real-Wold Use Cases

For the image generation, generative models like GANs are used to generate realistic images. Again, they can be used for tasks, like creating artwork, synthesizing images of human faces, or transforming sketches into photorealistic images.

For text generation, large language models like GPT 3, which are generative in nature, can create human like text. This has applications in content creation, like writing articles, generating ideas. And again, conversational AI, like chat bots, customer service agents. They are also used in programmings for code generation and debugging, and much more. 

For music generation, generative AI models can also be used. They create new pieces of music after being trained on a specific style or collection of tunes. A famous example is OpenAI's musenet.

Generative AI is also used in pharmaceutical industry for drug discovery, which can propose novel molecular structures for potential new drugs, significantly speeding up the early stages of drug discovery.

![Generative AI Use Cases](../images/generative_ai_uses_cases.png)

# Introduction to Large Language Models (LLM)

Large Language Models (LLMs) are a type of artificial intelligence models built to understand, generate, and process human language at a massive scale. 

They were primarily designed for sequence to sequence tasks such as machine translation, where an input sequence is transformed into an output sequence.

## LLM Features

- Based on deep learning architectures such as transformers
- Trained on vast amount of text data to learn language patterns and relationships
- Massive number of parameters usually in order of millions or even billions
- Ability to comprehend and understand natural language text at a semantic level (they can grasp context, infer meaning, and identify relationships between words and phrases)
- Remarkable capabilities in natural language understanding and generation
- Perform very well in various NLP tasks such as:
    - sentiment analysis
    - question and answering
    - language translation
    - summarization
    - named entity recognition

## History of LLMs

![History of LLMs](../images/history_of_llms.png)

## Model Size and Parameters

**Model size and parameters are crucial aspects of large language models and other deep learning models. They significantly impact the models capabilities, performance, and resource requirements.

The **model size** refers to the amount of memory required to store the model's parameter and other data structures. Larger model sizes generally led to better performance as they can capture more complex patterns and representation from the data.

The **parameters** are the numerical values of the model that change as it learns to minimize the model's error on the given task. In the context of LLMs, parameters refer to the weights and biases of the model's transformer layers.

*Parameters are usually measured in terms of millions or billions. For example, GPT-3, one of the largest LLMs to date, has 175 billion parameters making it extremely powerful in language understanding and generation.*

The **tokens** represent the individual units into which a piece of text is divided during the processing by the model. In natural language, tokens are usually words, subwords, or characters. Some models have a maximum token limit that they can process and longer text can may require truncation or splitting. 

Balancing model size, parameters, and token handling is crucial when working with LLMs. 

*The size and complexity of a language model, including the number of parameters (weights) and tokens have a profound impact on its capabilities and performance. Larger models with more parameters tend to have a better understanding of language and can generate more coherent and contextually relevant text. Larger models, however, require substantial computational resources, including GPUs and memory, for both training and inference.*

![LLMs](../images/llms.png)

## Bigger models are NOT always better!

1. Model size and numbers of tokens should be scaled equally
2. Scaling to larger data sets only beneficial when data is high-quality
3. Difficult to expand data set size by a large degree
4. Focus must be on high-quality data, though larger models perform better

## Applications of LLMs

1. Text Classification
    - Spam Detection
    - Sentiment Analysis
    - Content Categorization
2. Question Answering
    - Q&A Systems
    - Chatbots
3. Text Generation
    - Language Translation
    - Text Summarization
4. Document Summarization
    - Extracting Key Information


# LLM and Transformer Model

Understanding language is difficult for computers and AI systems. The reason being the attributes often have meanings based on context.

**Sequence Models** are used to solve problems, where the input data is in form of sequences that is ordered lists of data points or events. The goal in sequence problems is to find patterns dependencies or relationships within the data and make predictions, classification, or generate new sequences based on that understanding.

Common example of sequence models includes:
- Natural Language Processing (NLP)
- Speech Recognition
- Music Generation
- Gesture Recognition
- Time Series Analysis

## Recurrent Neural Networks (RNNs)

**Recurrent Neural Networks (RNNs)** are a class of neural network architectures specifically designed to handle sequential data. 

Unlike traditional feed forward neural networks, which is unidirectional and only goes from input to output, RNNs have a feedback loop that allows information to persist across different time steps, making them well-suited for tasks involving sequences of data.

The key feature of RNN is their ability to maintain an internal state, often referred to as the **hidden state or memory**, which is updated as the network processes each element in the sequence. This hidden state is then used as input to the network for the next time step, allowing the model to capture dependencies and patterns in the data that are spread across time. 

![Recurrent Neural Networks (RNNs)](../images/rrns.png)

## Transformers

Sequential models, such as RNNs and LSTM process input data one element at a time, maintaining a hidden state that summarizes the previous elements information. While this works well for short sequences, it becomes problematic when dealing with long sentences or documents. 

As the sequence grows, the model's ability to retain relevant context and dependencies weakens, leading to a phenomena called **vanishing gradient**. Consequently, long range dependencies becomes challenging to capture, limiting the model's understanding of the entire sequence.

So what is the solution? The solution is **transformers**. 

It's like model has a bird's eye view of the entire sentence and can see how all the words relate to each other. This allows it to understand the sentence as a whole instead of just a series of individual words. Transformers with their **self-attention mechanism** can look at all the words in the sentence at the same time and understand how they relate to each other.

Transformer is a type of deep learning model that was introduced, again, in the paper [Attention Is All You Need](https://arxiv.org/abs/1706.03762), in 2017. And it differs significantly from RNN and LSTM models.

Through self-attention, it allows each word in the input sequence to attend to all other words, determining the relevance and importance of each word concerning the entire sequence. It has encoded decoder architecture, where encoded processes the input sequence, whereas the decoder generates the output sequence. 

![Transformers](../images/transformers.png)# Transformer Walkthrough

The transformer architecture is designed to handle sequential data, such as sentences, in natural language by using a mechanism called **self-attention**.

The self-attention mechanism allows the model to weigh the importance of words, or tokens, within a sequence with respect to each other, enabling the model to focus on relevant context, regardless of the distance between tokens. 

Transformer architecture eliminates the need for recurrent or convolutional layers that were common in previous sequence modeling architectures, such as RNNs and LSTMs. 

## Encoder Decoder

Transformer models have two main parts:

- Encoder
- Decoder 

Both parts are made up of layers and each layer has its own attention mechanism:
- the encoder reads the input sentence, for example, a sentence in English, and uses the attention mechanism to create a new representation of the sentence that captures the meaning of the words and their connections
- the decoder then uses this information to generate output sentence, for example, a translation of the input sentence in English into French using its own attention mechanism

## Transformer Model Types

Each architecture type is chosen based on the specific requirements of the task, whether it involves understanding context, generating sequences, or both.

![Transformers Model Types](../images/transformer_types.png)

## Simple Transformer Architecture

 The simple transformer architecture involves:

 1. **Tokenization**
    - it involves breaking down the sentence into smaller pieces called **tokens**
    - tokens can be short as one character or as long as one word
    - the choice of how to break down the sentence depends on the specific tokenizer used. 
 2. **Embedding**
    - each token is converted into a numerical form called **vector** that the model can understand
    - these vectors are created in a way that captures the meaning of the word
    - words that have similar meanings will have similar vectors (e.g. "dog" and a "canine")
 3. **Positional Encoding**
    - the model needs to know the order of the words in the sentence because the meaning of a sentence can change depending on the order of its words
    - the model adds information about the position of each word in the sentence to their corresponding vectors
 4. **Transformer**
    - each transformer block is made up of two parts: an **attention** and a **feed forward**
    - the attention part helps the model understand the context of each word
    - the feed forward part applies a specific function, known as the feed forward function, to each word individually
 5. **Softmax**
    - the model generates a list of scores for each word in the vocabulary
    - the model uses the softmax function to turn these scores into a probability distribution
    - these steps are then repeated for each word in the sentence
    
    ![Transformer Architecture](../images/transformer_architeture.png)

# Prompt Engineering

A **prompt** is the input or initial text provided to the model to elicit a specific response or behavior. So this is something which you write or ask to a language model.

Prompt Engineering is the process of designing and formulating specific instructions or queries to interact with a large language model **effectively**.

The goal of prompt engineering is to ensure that the language model understands the user's intent correctly and provide accurate and relevant responses. The use of prompts with no examples is sometimes referred to as **zero shot** learning. Successful prompts often rely on the practice of **one shot** or **few shot** learning. This refers to the inclusion of one or more examples of the desired behavior of the model, typically by including input and output pairs. Few shot inference involving more than one example is called **in-context learning**.

*In-context learning refers to the capability of generative large language models (LLMs) to learn and perform new tasks without further training or fine-tuning. Instead of modifying the model permanently, users can guide the model's behavior by providing a few examples of the target task through the input prompt. This is particularly useful when direct access to the model is limited, such as when using it through an API or user interface.*

## Best Practices

1. Try writing the prompt input in multiple ways

2. Describe the task with clear and specific instructions

3. Handle edge cases and conditions responses

4. Give examples for completing the task for a desirable outcome# LLM Fine Tuning

Tthe life cycle of a Large Language Model involves several stages:

- **Pre-training**
    - the model learns grammar, facts, reasoning abilities, and general language understanding
    - the model predicts the next word in a sentence given the previous words, which helps it capture relationships between words and the structure of language
- **Fine Tuning**
    - the model's weights are initialized
    - fine tuning can involve supervised learning on labeled data for specific tasks, such as sentiment analysis, translation, or text generation
    - the model is fine tuned on specific tasks using a smaller domain specific data set
    - the weights from pre-training are updated based on the new data
- **Prompt Engineering**
    - this phase craft effective prompts to guide the model's behavior in generating specific responses
    - different prompt formulations, instructions, or context can be used to shape the output
- **Evaluation and Iteration**
    - models are evaluated using various metrics to access their performance on specific tasks
    - iterative refinement involves adjusting model parameters, prompts, and fine tuning strategies to improve results
    - you also do few shot and one shot inference
    - if needed, you further fine tune the model with a small number of examples
    - **bias mitigation** and consider the **ethical concerns** (you need to implement measures to ensure fairness in inclusivity and responsible use)
- **Deployment and Ongoing Maintenance**
    - deployed models can perform tasks, such as text generation, translation, summarization, and much more
    - you also perform monitoring and maintenance
    - you continuously monitor the model's performance and output to ensure it aligns with desired outcomes
    - you also periodically update and retrain the model to incorporate new data and to adapt to evolving language patterns

This overall life cycle can also consist of a feedback loop, whether you gather feedbacks from users and incorporate it into the models improvement process. RLHF, which is Reinforcement Learning with Human Feedback, is a very good example of this feedback loop.

You also research and innovate as a part of this life cycle, where you continue to research and develop new techniques to enhance the model capability and address different challenges associated with it.

![LLM Lifecycle](../images/llm_lifecycle.png)

## Fine Tuning

In the context of LLM, fine tuning refers to the process of further training a pre-trained language model on a specific task or domain to make it more specialized and accurate for that particular use case.

Fine tuning is required for:
- task specific adaptation
- domain specific vocabulary
- efficiency and resource utilization
- ethical concerns

Fine tuning reuses the knowledge from pre-trained models saving time and resources. Again, fine tuning requires fewer iterations to achieve task specific competence. Shorter training cycles expedite the model development process. And again, it conserves computational resources, such as GPU memory and processing power. 

Pre-trained models learns from diverse data and those potentially inherit different biases. So fine tune might not completely eliminate biases but careful curation of task specific data ensures avoiding biased or harmful vocabulary. # AI Services

Oracle AI is this portfolio of cloud services for helping organizations take advantage of all data for the next generation of scenarios. The foundations of AI services and ML services layer is data.

![Oracle AI Stack](../images/ai_services.png)

OCI AI services is a collection of services with pre-built machine learning models that make it easier for developers to build a variety of business applications. The models can also be custom trained for more accurate business results.

The different services provided are:

- **digital assistant**: AI driven interfaces that help users accomplish a variety of tasks with natural language conversations
    - interact with the user
    - lists what it can do
    - routes user's request to skills
    - handles disambiguation

- **Language**: you can process unstructured text to extract insights without data science expertise
    - pretrained models
        - language detection
        - sentiment analysis
        - key phrase extraction
    - custom models (domain specific data sets)
        - named entity recognition
        - text classification
    - text translation
        - translate text across numerous languages

- **Vision**: you can upload images to detect and classify objects in them
    - pretrained models
        - object detection
        - image classification
        - optical character recognition
    - custom models
        - detecting the location of custom objects in an image and providing a bounding box
        - identify objects and scene based features in an image
- **Speech**: you can convert media files containing human speech into highly exact text transcriptions

- **Document Understanding**: you can upload documents to detect and classify text and objects in them
    - *OCR (Optical Character Recognition)*: can detect and recognize text in a document
    - *Text Extraction*: provides the word-level/line-level text and the bounding box (coordinates of where the text is found)
    - *Key Value Extraction*: extracts a predefined list of key value pairs of information from receipts, invoices, passports, etc.
    - *Table Extraction*: extracts content in tabular format, maintaining the row and column relationship of cells
    - *Classification*: classifies documents into different types
- **Anomaly Detection**: it is the identification of rare items, events, or observations in data that differ significantly from the expectation
    - analyzes large volume of multivariate or univariate time series data
    - designed to help with analyzing large amounts of data and identifying the anomalies at the earliest possible time with maximum accuracy

## Access Methods

OCI AI services provide multiple methods for access:

- OCI Console
    - provides easy to use browser-based interface
    - enable access to notebook sessions and all service features
- REST API
    - provides access to service functionality
    - requires programming expertise
- Language SDK 
    - provides programming language SDKs
- CLI
    - provides quick access and full functionality without the need for scripting# ML Services

OCI Data Science is the cloud service focused on serving the data scientist throughout the full machine learning life cycle with support for Python and open source.

Oracle Database's Machine Learning capabilities are designed to eliminate the need to move data out of the database for Machine Learning tasks. This is a significant advantage because it reduces data latency, enhances security, and simplifies the overall architecture of data-driven applications. By providing in-database Machine Learning, Oracle empowers users to perform Machine Learning tasks directly within the database, leveraging its computational power and efficiency.

![OCI Data Sciences](../images/oci_data_science_components.png)

## CORE Principles

There are three core principles of OCI Data Science:

- **Accelerated**. The first principle is about accelerating the work of the individual data scientist. OCI Data Science provides data scientists with open source libraries along with easy access to a range of compute power without having to manage any infrastructure. It also includes Oracle's own library to help streamline many aspects of their work.

- **Collaborative**. It goes beyond an individual data scientists productivity to enable data science teams to work together. This is done through the sharing of assets, reducing duplicative work, and putting reproducibility and auditability of models for collaboration and risk management. Third is enterprise grade. 

- **Enterprise grade**. That means it's integrated with all the OCI Security and access protocols. The underlying infrastructure is fully managed. The customer does not have to think about provisioning compute and storage and the service handles all the maintenance, patching, and upgrades so user can focus on solving business problems with data science. 

## What, Whom, Where ad How of Data Science

![OCI Data Sciences](../images/oci_data_science.png)

## Features and Terminology

- **Projects**. The projects are containers that enable data science teams to organize their work. They represent collaborative work spaces for organizing and documenting data science assets, such as notebooks sessions and models.

- **Notebook Sessions**. Notebook sessions provide a JupyterLab environment with pre-installed open source libraries and the ability to add others. Notebook sessions are interactive coding environment for building and training models.

- **Conda Environment**. It's an open source environment and package management system and was created for Python programs. It is used in the service to quickly install, run, and update packages and their dependencies. Conda easily creates and switches between environments in your notebooks sessions. 

- **Accelerated Data Science (ADS) SDK**. Oracle's Accelerated Data Science ADS SDK is a Python library that is included as part of data science. ADS has many functions and objects that automate or simplify the steps in the data science workflow, including connecting to data, exploring, and visualizing data. 

- **Models**. Models define a mathematical representation of your data and business process. You create models in notebooks, sessions, inside projects. 

- **Model Catalog**. The model catalog is a place to store, track, share, and manage models. The model catalog is a centralized and managed repository of model artifacts. A stored model includes metadata about the provenance of the model, including Git related information and the script. Models stored in the model catalog can be shared across members of a team, and they can be loaded back into a notebook session. 

- **Model Deployments**. Model deployments allow you to deploy models stored in the model catalog as HTTP endpoints on managed infrastructure. Deploying machine learning models as web applications, HTTP API endpoints, serving predictions in real time is the most common way to operationalize models. HTTP endpoints or the API endpoints are flexible and can serve requests for the model predictions. 

- **Jobs**. Jobs enable you to define and run a repeatable machine learning tasks on fully managed infrastructure.# AI Infrastructure

OCI AI Infrastructure is mainly composed of:
- GPU based instances: they can be virtual machines or bare metal machines. 
- High performance cluster networking: it allows instances to communicate to each other
- Super clusters: they are a massive network of GPU instances with multiple petabytes per second of bandwidth.
- Fully managed storage: from a single byte to exabytes without upfront provisioning are also available.

## GPU Architecture

ML and AI needs lots of repetitive computations to be made on huge amounts of data. Parallel computing on GPUs is designed for many processes at the same time. A GPU is a piece of hardware that is incredibly good in performing computations.

GPU has thousands of lightweight cores, all working on their share of data in parallel. This gives them the ability to crunch through extremely large data set at tremendous speed. 

GPU instances are ideally suited for model training and inference.

GPUs are specialized hardware designed primarily for accelerating tasks related to graphics rendering and parallel processing.

## Super Clusters

OCI AI Superclusters are specifically designed to handle demanding AI workloads that require significant computational power and scalability. They are optimized to provide high performance for complex tasks such as training large Machine Learning models, deep learning, and other compute-intensive AI tasks.

## RDMA

RDMA is essentially, in a nutshell, is a technology that allows for data transfer or network communication that bypasses CPU, goes from one machine to another without any CPU interference. And this allows things like GPUs to communicate at extremely low latency, high bandwidth with low overhead from a CPU perspective. # Responsible AI

The guiding principles for AI to be trustworthy are:
- **AI should be lawful**, complying with all applicable laws and regulations
- **AI should be ethical**, that is it should ensure adherence to ethical principles and values that we uphold as humans
- **AI should be robust**, both from a technical and social perspective because even with the good intentions, AI systems can cause unintentional harm

## AI Ethics Principles

1. Respect for human autonomy
2. Prevention of harm
3. Fairness
4. Explicability

AI that follows the ethics principles is **Responsible AI**.

![Responsible AI](../images/responsible_ai.png)

## Responsible AI Cycle and Roles

![Responsible AI Cycle and Roles](../images/responsible_ai_cycle.png)# OCI Language

OCI Language provides models trained on industry data to perform language analysis with no data science experience needed. 

It has five main capabilities:
1. it detects the language of the text
2. it identifies entities in text (e.g. names, places, etc.)
3. it identifies the sentiment of the text
4. it identifies key phrases in the text that represent the important ideas or subjects
5. it classifies the general topic of the text from a list of 600 categories and subcategories# OCI Speech

OCI Speech main capabilities:

- it transcribes audio and video files into text using advanced deep learning techniques
- no data science experience required
- it processes data directly in object storage
- it generates timestamped, grammatically accurate transcriptions

OCI Speech features:

- itsupports multiple languages
- it has batching support where multiple files can be submitted with a single call
- it has blazing fast processing.

    *it can transcribe hours of audio in less than 10 minutes by chunking up your audio into smaller segments, and transcribing each segment, and then joining them all back together into a single file*
- it provides a confidence score, both per word and per transcription
- it punctuates transcriptions to make the text more readable and to allow downstream systems to process the text with less friction
- it has SRT file support 

    *SRT is the most popular closed caption output file format and with this SRT support, users can add closed captions to their video*
    
![OCI Speech](../images/oci_speech.png)# OCI Vision

OCI Vision provides two main capabilities:

1. Image Analysis 
2. Document AI

## Image Analysis

Image analysis analyzes photographic images. 

**Object Detection** is the feature that detects objects inside an image using a bounding box and assigning a label to each object with an accuracy percentage. Object detection also locates and extracts text that appears in the scene, like on a sign.

**Image classification** will assign classification labels to the image by identifying the major features in the scene. One of the most powerful capabilities of image analysis is that, in addition to pretrained models, users can retrain the models with their own unique data to fit their specific needs. 

## Document AI

Document AI is used for working with document images.

The features of document AI are:

- **Text Recognition**, also known Optical Character Recognition (OCR)

    This extracts text from images, including non-trivial scenarios, like handwritten texts, plus tilted, shaded, or rotated documents.

- **Document Classification** 

    It classifies documents into 10 different types based on visual appearance, high level features, and extracted keywords. This is useful when you need to process a document, based on its classification, like an invoice, a receipt, or a resume.

- **Language Detection** 

    It analyzes the visual features of text to determine the language rather than relying on the text itself. 
    
- **Table Extraction** 

    It identifies tables in docs and extracts their content in tabular form. 
    
- **Key value extraction**

    It finds values for 13 common fields and line items in receipts, things like merchant name and transaction date. 

OCI Document Understanding is a service in Oracle Cloud Infrastructure designed for automating document processing tasks, such as extracting information from documents, automating data entry, and streamlining document-based workflows. It's used for tasks such as invoice processing, form recognition, and document classification.# Anomaly Detection

OCI Anomaly Detection identifies anomalies in time series data**. The unique feature of this service is that it finds anomalies, not just in a single signal, but across many signals at once. That's important because machines often generate multiple signals at once and the signals are often related.

The service contains algorithms for both multi-signal, as in multivariate, single signal, as in univariate anomaly detection, and it automatically determines which algorithm to use based on the training data provided. 

The multivariate algorithm is called MSET-2, which stands for Multivariate State Estimation technique, and it's unique to Oracle. The 2 in the name refers to the patented enhancements by Oracle labs that automatically identify and fix data quality issues resulting in fewer false alarms and more accurate results.

Unlike some of the other AI services, OCI anomaly detection is always trained on the customer's data. It's trained using actual historical data with no anomalies, and there can be as many different trained models as needed for different sets of signals.

One of the most obvious applications of this service is for **Predictive Maintenance**. Early warning of a problem provides the opportunity to deploy maintenance resources and schedule downtime to minimize disruption to the business.

Each trained model is accessible through a REST API and an HTTP endpoint. Additionally, programming language-specific SDKs are available for multiple languages, including Python. 

**Timestamps must follow the ISO 8601 format.

## How To Train an Anomaly Detection Model

1. Obtain training data

    The data must contain no anomalies and should cover the normal range of values that would be experienced in a full business cycle.

2. Upload training data to Object Storage

3. Create a data set fro the training data

4. Train the model
    
    Training a model requires a single data file with no anomalies that should cover a complete business cycle, which means it should represent all the normal variations in the signal. 
    
    
During training, OCI anomaly detection will use a portion of the data for training and another portion for automated testing. The fraction used for each is specified when the model is trained.

![Model Training](../images/model_training_1.png)

When model training is complete, it's best practice to do another test of the model with a data set containing anomalies to see if the anomalies are detected and if there are any false alarms. 

![Model Training](../images/model_training_2.png))

Based on the outcome, the user may want to retrain the model and specify a different False Alarm Probability (FAP). 

The FAP is the probability that the model would produce a false alarm. The false alarm probability can be thought of as the *sensitivity of the model*. The lower the false alarm probability, the less likelihood of it reporting a false alarm, but the less sensitive it will be to detecting anomalies. 

Selecting the right FAP is a business decision based on the need for sensitive detections balanced by the ability to tolerate false alarms.

Once a model has been trained and the user is satisfied with its detection performance, it can then be used for **inferencing**. 

## Univariate Models VS Multivariate Models

When training OCI anomaly detection models, the user does not need to specify whether the intended model is for multivariate or univariate data. It does this detection automatically. 

![Univariate Models VS Multivariate Models](../images/univariate_vs_multivariate.png)# Oracle AI APIs

How does a Data Scientist take advantage of Oracle AI capabilities ? 
1. REST API
2. Language SDKs (Python, Java, Go, etc..)

Before you can invoke the SDK, you have to obtain an **API Signing Key**. 

You can obtain an API Signing Key from your user profile in the OCI Console, then you save that key as a file to your local machine. The API Signing Key also provides commands to be added to a config file that the SDK expects to find in the environment, where the SDK code is executing. The config file then references the key file. Once these files are prepared on your local machine, you can upload them to the Notebook session, where you will execute SDK code for the AI service.

The API Signing Key and config file can be reused with any of your notebook sessions, and the same files also work for all of the AI services. So the files only need to be created once for each user and tenancy combination.