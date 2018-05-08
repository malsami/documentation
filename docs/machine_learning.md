### Machine Learning 

We are using machine learning for schedulability analysis to see whether there are patterns in the data that indicates future behavior and whether this is a viable approach for the future analysis. Given the implementation of newer algorithms and the ease of use, it is worthwhile to pose the problem to be operated by machine learning algorithms. Since we are using real-time systems, we must also analyze the resources that the algorithms are using and whether they are viable for the ECUs that will be running the tasks. Certain algorithms may be more on the offline training phase while others on the online. All of these are factors that will be considered when analyzing the models. 

 We are using *[Deep Learning](Deep_Learning.md)* and *[Shallow_Learning](Shallow_Learning.md)* to compare the approaches. It is easy to throw Deep Learning at the problem and expect it to work. However, to get a more complete analysis, it is important to investigate as many viable choices as we can get. Furthermore, different data-mining models can reveal different information about the data that we can use to fit our pre-trained model more. 

Furthermore, shallow learning is beneficial becaues they are relatively lightweight compared to deep learning models and are easier to scale.We plan on testing multiple models for both the Deep Learning and Shallow Learning approach. We are not just trying to find the best approach, but to analyze which approaches are the best and what information we cand hope to gain from this. Please refer to the documents for more information regarding these approaches. 