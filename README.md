# SemEval-2021-Task-2
 Task 2: Zero Shot and Few Shot Learning forMulti-lingual and Cross-lingual Word Sense Disambiguation. Post by UoB_UK
 
 The paramaters are fixed in this python file. 
 
 job = Job(seed=4568) - can be used to change the random seed.
 
 job.train - with large and base xlm-roberta package is used for training XLM-RoBERTa Base + MLP, Zero Shot and XLM-RoBERTa Large + MLP, Zero Shot.
 job.finetune - with large and base xlm-roberta package can be used for XLM-RoBERTa Base + MLP, Few-shot and XLM-RoBERTa Large + MLP, Few-shot.
 job.few_shot_train - with large xlm-roberta package can be used for XLM-RoBERTa Large + KNN, Few-shot.
 
 job.predict("test") - can be generated test result for submit to the codalab Semeval task2 official competition.

XLM-RoBERTa Base + MLP, Zero Shot uses random seed 2020.

XLM-RoBERTa Large + MLP, Zero Shot uses different random seeds for different sub-task:
EN-EN, AR-AR, EN-AR uses 4568,
FR-FR, RU-RU, EN-FR, EN-RU uses 6893,
ZH-ZH,EN-ZH uses 1234.


XLM-RoBERTa Base + MLP, Few-shot uses random seed 4568.
XLM-RoBERTa Large + MLP, Few-shot uses random seed 4568.
XLM-RoBERTa Large + KNN, Few-shot uses random seed 6893.

For more detail please contact me.
WXL885@student.bham.ac.uk
