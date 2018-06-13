# Intention
This is a repository of all the things I would like to convert into projects, preferably using both R and Python.  Really it's somewhere for me to store all my notes, links, blogs, tweets, hallway whispers, I would like to revisit at some point.  Step 1. organize notes.

# Ambition  

+  structural time series; aka kalman filter; state space modeling   
		+ R package dlm and dse  

+ Bayesian structural time series 
		+ R package BRMS R package
+ Frequency Pattern growth tree -- use for seeing what things happen at the same time
+ ARIMA modeling  
+ exponential smoothing  
+ GAMS  
+ Neural Networks  
+ Natural Language Processing  
		+ sentiment analysis   
		+ term frequency-inverse document frequency -- TF-IDF (http://www.tfidf.com/)   
		+ creating of word cloud in pre-defined shape and color     
		+ Latent Dirilecht allocation --  used to discover underlying topics (http://blog.echen.me/2011/08/22/introduction-to-latent-dirichlet-allocation/)   
		+ (https://algorithmia.com/tags/text-analysis)     
		
+ Poisson Regression  	
+ Random Forest  
+ Gradient boosting  	
+ stanford’s LP suite (https://stanfordnlp.github.io/CoreNLP/  ) - - tool/framework includes tokenization (text word splitting), tagging part of speech, grammar parsing (noun vs. verbs), named entity recognition, etc.  Else give this python utility a try: http://www.nltk.org/ ;  Similar to the stanford library - supports tokenizing, parsing, named entities identification  
+ DeepAR forecasting algorithm at Amazon (https://docs.aws.amazon.com/sagemaker/latest/dg/deepar.html) [See White paper](https://pdfs.semanticscholar.org/4eeb/e0d12aefeedf3ca85256bc8aa3b4292d47d9.pdf)


# Piping to learn
+ Containers   
		+ Docker   
		+ S3 cluster  
		+ ECR  
+ Amazon Athea Optimization
+ Amazon SageMaker  
		+ How to productionize ML models  
		+ End-toEnd ML Platform  
		+ Zero setup  
		+ Flexible model training  
			+ Tensor Flow    
			+ mxnet  
			+ Gluon  
		+ scales out with demand.  Pay by demand, by second.  
		+ UX -- sagemaker console + Jupyter notebooks   
			+ Use SageMaker's hosted Notebook Instances  
			+ or Apache Spark through EMR and the SageMaker Spark SDK  
			+ or SageMaker's Console for a point and click experience  
			+ of your own device (EC2, laptop, etc)  
		+ Training/Hosting  
			+ Custom models via Docker/ECR  
			+ Low latency, high throughput, and high reliability  
			+ Zero downtime deployment and A/B testing  
			+ Trained model artifact is uploaded to S3
		+ Built-in algorithms  
			+ XGBoost, FM, Linear, and DeepAR Time-Series Forecasting for supervised learning  
			+ Kmeans, PCA, and Word2Vec for clustering and pre-processing  
			+ Image Classification  
		+  Native TensorFlow and MXNet support
		+ Build your own algorithm  
			1. Pick your preferred framework  
				+ SciKit learn  
				+ R    
				+ PyTorch    
				+ Java  
			2. ... upload to Docker .. then...   
		+ Hyperparameter optimization (automatic model tuning)  
		+ Spark SDK reads from S3  
		+ SageMaker instances are typically smaller, not typically used for data munging.  Data has been munged  
		+ [See sagemaker Jupyter notebook repository](https://github.com/robperc/sagemaker-workshop)



# Regularization notes:

+   L1 still is a shrinkage penalty, it just shrinks coefficients exactly to zero in a finite amount of time, where L2 shrinks them asymptotically to zero.   
+ L2 is preferred over L1 for several reasons.  L2 is a shrinkage penalty, where L1 will just set values to zero.  So L2 "moderates" your parameter values, while L1 just eliminates them.  Also, L2 is differentiable everywhere, so it makes back 




# Neural Nets notes:

+ Paper on Dropout: http://www.cs.cmu.edu/~rsalakhu/papers/srivastava14a.pdf  
+ As for dropout, it's kind of like what you do in random forest where you only use a subset of variables in each tree.  You're suppressing the signal from some features so that other features have a chance to stand out.  It also helps decorrelate variables, so they stand more on their own.  
+ NN for NLP best practices: http://ruder.io/deep-learning-nlp-best-practices/index.html  





