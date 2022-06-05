# Project in MAI AIAPP Computer Vision
## Authors
- Michael Kranl
- Alexander Zulechner
## Assignment questions
- What accuracy can be achieved? What is the accuracy of the train vs. test set?
  - Exp1: Acc ~64%, Train-acc ~98%, Test-acc ~65%
  - Exp2: Acc ~60%, Train-acc ~63%, Test-acc ~60%
  - Exp3: Acc 7% -> bad :(
- On what GPU did you train it? What was the inference time?
  - trained in Google Collab ((parts) of a Tesla K80 GPU were assigned), inference time was several ms
- What are the number of parameters of the model?
  - Exp1+2: 90709913
  - Exp3:  489148025
- Which categories are confused most by the algorithm? Show results in a confusion matrix.
   - See notebooks
- Can you observe any differences in the “real-world” vs. trainings/test-set?
  - Inference on real-world images is quite bad (1/14 images was predicted correctly in Exp2)
