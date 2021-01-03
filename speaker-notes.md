## Speaker Notes

### Intro

You’ve probably all heard about AI and ML. Given the attention machine learning has received and the sophisticated problems it is solving, it may seem like magic. But it is not. In a nutshell, machine learning uses mathematical algorithms to learn and analyze data to make predictions and take decisions in the future. But before we start to dive into the topic, let’s jump and examine the origins of ML and some of its recent milestones.

### History of the ML

The concept of machine learning came into the picture in **1950**, when **Alan Turing** published an article answering the question, “Can machines think?”.
In **1957**, **Frank Rosenblatt** designed the first neural network for computers, now commonly called the **Perceptron model**. The Perceptron algorithm was designed to classify visual inputs, categorizing subjects into one of the two groups.
In **1959**, **Bernard Widrow** and **Ted Hoff** created two network models called **Adeline**, that could detect binary patterns and **Madeline**, that could eliminate echo on phone lines.
**Gerald Dejong** in **1981** introduced the concept of **explanation-based learning**, in which a computer analyzes data and creates a general rule to discard unimportant information.
During the **1990s**, work on machine learning shifted from a knowledge-driven approach to a more data-driven approach. Scientists began creating programs for computers to analyze large amounts of data and draw conclusions or “learn” from results.
In **2002**, using a combination of ML, natural language processing and information retrieval techniques, IBM’s Watson beat two human champions in a game of Jeopardy.
In the **2016**, Google’s AlphaGo program became the first computer program to beat a professional human using a combination of ML and tree search techniques.
Since the start of the **21st century**, many businesses ventured into creative learning projects. Google Brain, AlexNet, DeepFace, DeepMind, OpenAI, Amazon ML Platform and ResNet are some large projects. Amazon, Netflix, Google, Salesforce and IBM are dominating the IT industry with ML.
Where ML is used
Today, machine learning algorithms enable computers to communicate with humans, autonomously drive cars, write and publish sport match reports, predict natural disasters or find terror suspects.

Here are the most common uses of ML:

- Computational finance
- Image processing and computer vision
- Computational biology
- Energy production
- Automotive, aerospace, and manufacturing
- Natural language processing
  Really exciting, isn’t it? Now, let’s talk about what ML is.

### What is machine learning?

Machine learning is an application of artificial intelligence (AI) that provides systems the ability to automatically learn and improve from experience without being explicitly programmed.
Machine learning focuses on the development of computer programs that can access data and use it to learn for themselves.
In machine learning, the underlying algorithm is selected or designed by a human. However, the algorithms learn from data, rather than direct human intervention, about the parameters that will shape a mathematical model for making predictions. A data set is used to train a mathematical model so that when it sees similar data in the future, it knows what to do with it. Models typically take data as an input and then output a prediction of something of interest.
Machine Learning Techniques
Machines learn in different ways with varying amounts of “supervision”: supervised, unsupervised, and reinforced. Supervised learning is the most deployed form of ML and also the easiest. However, unsupervised learning doesn’t require as much data and has the most practical use cases.

#### Supervised Learning

Machines often learn from sample data that has both an example input and an example output.
A supervised learning algorithm takes a known set of input data and known responses to the output data and trains a model to generate reasonable predictions for the response to new data. Given enough of these input-output samples, the machine learns how to construct a model that is consistent with the samples it trained on.
From there, the model can be applied to new data that it has never seen before. After learning from sample data, the model applies what it has learned to the real world.
Supervised learning uses classification and regression techniques to develop predictive models.

##### Classification

The goal of a classification problem is to determine what group a given input belongs to. A classic example is categorizing animal pictures into a cat group and a dog group.
The machine is trained on data with many examples of inputs (like an image of an animal) along with corresponding outputs, often called labels (like “cat” or “dog”). Train the model with a million pictures of cats and dogs, and it should be able to classify a picture of a new dog that wasn’t in the training data.

##### Regression

Like classification, regression is also about inputs and corresponding outputs. But outputs for classification are typically discrete types (cat, dog), outputs for regression are a general number. In other words, it’s not a 0 or 1, but a sliding scale of possibility. For example, given a radiological image, a model could predict how many more years the associated individual will be sick or healthy.

#### Unsupervised Learning

In unsupervised learning, the machine learns from data for which the outcomes are not known. It’s given input samples, but no output samples.
For instance, imagine you have a set of documents that you would like to organize. For example, some documents may be about sports, others about history, and still others about the arts. Given only the set of documents, the objective is to automatically learn how to cluster them into types.
Clustering is the most common unsupervised learning technique. It is used for exploratory data analysis to find hidden patterns or groupings in data. Applications for cluster analysis include gene sequence analysis, market research, and object recognition.

#### Reinforcement Learning

Reinforcement learning is like unsupervised learning in the sense that outputs are usually not given.
The central concept of reinforcement learning is based around an “agent” (a computer or robot) that is interacting with an “environment” (here defined as everything that is not the agent).
The agent performs actions on the environment (for instance, a robot takes a step forward). Then, the environment will provide some sort of feedback to the agent, usually in a form called the “reward.”
By “reward”, we don’t mean we give the machine a jolt of electrons. We literally just add to the program’s reward counter. The agent’s goal is to maximize the number in that counter. Critically, however, no one is telling the agent how to maximize the reward or explaining why it gets a reward. That’s what the agent figures out for itself by taking actions and observing its environment.

### ML frameworks and libraries

Machine learning relies on algorithms. Unless you’re a data scientist or ML expert, these algorithms are very complicated to understand and work with.
A machine learning framework, then, simplifies machine learning algorithms. An ML framework is any tool, interface, or library that lets you develop ML models easily, without understanding the underlying algorithms.
There are a variety of machine learning frameworks, geared at different purposes. Nearly all ML frameworks are written in Python. Python is the predominant machine learning programming language.
TensorFlow, PyTorch, and scikit-learn are the most popular ML frameworks. Still, choosing which framework to use will depend on the work you’re trying to perform. These frameworks are oriented towards mathematics and statistical modeling (machine learning) as opposed to neural network training (deep learning).
Here’s a quick breakdown of these popular ML frameworks:

- TensorFlow and PyTorch are direct competitors because of their similarity. They both provide a rich set of linear algebra tools, and they can run regression analysis.
- Scikit-learn has been around a long time and would be most familiar to R programmers, but it comes with a big caveat: it is not built to run across a cluster.
- Spark ML is built for running on a cluster.Works with Spark SQL dataframes and provides model analysis tools like the confusion matrix

THANK YOU FOR ATTENTION!
