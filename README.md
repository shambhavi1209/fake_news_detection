# Verifacts

Fake news refers to pieces of news that may be hoaxes and are generally spread through social media and other online platforms. It often contains false or exaggerated claims and is spread to further certain ideas or agendas. Fake news can be viralized by algorithms, leading users into filter bubbles.

## TfIdfVectorizer
TF and IDF: It uses two important concepts called "Term Frequency" (TF) and "Inverse Document Frequency" (IDF) to measure this importance.

Term Frequency (TF): This counts how often a word appears in a document. If a word appears frequently, it's considered important for that document.

Inverse Document Frequency (IDF): This measures how important a word is across all the documents in a collection. If a word appears frequently in one document but not in many others, it's considered more important.


## PassiveAggressiveClassifier

When the classifier makes a correct prediction, it stays passive and doesn't change much.
When the classifier makes a mistake, it becomes aggressive and adjusts its parameters to correct the error.

The PassiveAggressiveClassifier is known as an "online learning" algorithm. This means it can continuously learn from new data without needing to retrain the entire model from scratch. It adapts and updates its parameters as new examples are provided.

Unlike many other machine learning algorithms that aim to converge to an optimal solution, the PassiveAggressiveClassifier does not converge. Instead, it updates its parameters in an iterative manner, making small adjustments to minimize errors.

The PassiveAggressiveClassifier is commonly used in scenarios where data streams in continuously, and the model needs to adapt quickly to changes in the data. It's particularly useful for tasks like text classification, where new documents arrive over time.
