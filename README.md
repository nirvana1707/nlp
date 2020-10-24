# Natural Language Processing
Repo of NLP related approaches and code

## Experiments
This contains compilation of notes and POCs from courses and practical implementations. 

### W1
W1 looks at an array of starter NLP code ranging from text pre-processing, feature generation and applying classical machine learning models

Comparison of results from bow & tf-idf-

BOW

![alt text](https://github.com/nirvana1707/nlp/blob/main/experiments/w1/images/ROC_results_bow.PNG)

TF-IDF

![alt text](https://github.com/nirvana1707/nlp/blob/main/experiments/w1/images/ROC_results_tfidf.PNG)


### W2
W2 looks at implementing Named Entity Recognition using LSTM using TensorFlow on sample set of Twitter data

Sample output results -
-------------------- Train set quality: --------------------
processed 105778 tokens with 4489 phrases; found: 4777 phrases; correct: 3142.

precision:  65.77%; recall:  69.99%; F1:  67.82

	     company: precision:   80.71%; recall:   81.34%; F1:   81.02; predicted:   648

	    facility: precision:   64.23%; recall:   72.61%; F1:   68.16; predicted:   355

	     geo-loc: precision:   85.99%; recall:   88.76%; F1:   87.35; predicted:  1028

	       movie: precision:    0.00%; recall:    0.00%; F1:    0.00; predicted:     2

	 musicartist: precision:   34.88%; recall:    6.47%; F1:   10.91; predicted:    43

	       other: precision:   49.77%; recall:   70.81%; F1:   58.45; predicted:  1077

	      person: precision:   73.46%; recall:   90.29%; F1:   81.01; predicted:  1089

	     product: precision:   18.16%; recall:   24.21%; F1:   20.75; predicted:   424

	  sportsteam: precision:   71.17%; recall:   36.41%; F1:   48.17; predicted:   111

	      tvshow: precision:    0.00%; recall:    0.00%; F1:    0.00; predicted:     0

-------------------- Validation set quality: --------------------
processed 12836 tokens with 537 phrases; found: 349 phrases; correct: 164.

precision:  46.99%; recall:  30.54%; F1:  37.02

	     company: precision:   60.98%; recall:   48.08%; F1:   53.76; predicted:    82

	    facility: precision:   39.29%; recall:   32.35%; F1:   35.48; predicted:    28

	     geo-loc: precision:   72.73%; recall:   42.48%; F1:   53.63; predicted:    66

	       movie: precision:    0.00%; recall:    0.00%; F1:    0.00; predicted:     1

	 musicartist: precision:    0.00%; recall:    0.00%; F1:    0.00; predicted:     0

	       other: precision:   31.08%; recall:   28.40%; F1:   29.68; predicted:    74

	      person: precision:   47.62%; recall:   26.79%; F1:   34.29; predicted:    63

	     product: precision:    3.57%; recall:    2.94%; F1:    3.23; predicted:    28

	  sportsteam: precision:   14.29%; recall:    5.00%; F1:    7.41; predicted:     7

	      tvshow: precision:    0.00%; recall:    0.00%; F1:    0.00; predicted:     0

-------------------- Test set quality: --------------------
processed 13258 tokens with 604 phrases; found: 426 phrases; correct: 200.

precision:  46.95%; recall:  33.11%; F1:  38.83

	     company: precision:   67.35%; recall:   39.29%; F1:   49.62; predicted:    49

	    facility: precision:   54.55%; recall:   38.30%; F1:   45.00; predicted:    33

	     geo-loc: precision:   74.04%; recall:   46.67%; F1:   57.25; predicted:   104

	       movie: precision:    0.00%; recall:    0.00%; F1:    0.00; predicted:     0

	 musicartist: precision:   50.00%; recall:    3.70%; F1:    6.90; predicted:     2

	       other: precision:   25.89%; recall:   28.16%; F1:   26.98; predicted:   112

	      person: precision:   46.84%; recall:   35.58%; F1:   40.44; predicted:    79

	     product: precision:    0.00%; recall:    0.00%; F1:    0.00; predicted:    35

	  sportsteam: precision:   41.67%; recall:   16.13%; F1:   23.26; predicted:    12

	      tvshow: precision:    0.00%; recall:    0.00%; F1:    0.00; predicted:     0

