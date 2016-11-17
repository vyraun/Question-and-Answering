# Question-and-Answering
#


  This is a Deep learning model that projects questions and answers into a semantic space such that the question-answer pairs from the training set are closer to each other . It's written in torch.

  The baseline model is QA-LSTM from paper "Improved Representation Learning for Question Answer Matching" by Ming et al 2016 : http://www.aclweb.org/anthology/P/P16/P16-1044.pdf
  
  Training: th qa_lstm.lua -- To create a new network

          : th qa_lstm.lua load-- To  load an existing network 
  



# To customize your corpus:

 Make sure that the qa corpus have the following pattern:

\#question
"question text"
\#answer
"answer text"


 Place it in the folder make_corpus and run the following:
 the makeitlikeins.lua <your qa corpus >
   
