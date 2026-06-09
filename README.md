# Arabic-Medical-Question-Answering-Systems


The project aims to use Retrieval-Augmented Generation (RAG) for Arabic Medical Question-Answering Systems. The idea is to train large language models (such as Bloomz, AraBERT with/without BiLSTM, and AraT5) on Arabic medical datasets using publicly available information on the web. The model will take a question, retrieve relevant data from the web, and feed it, along with the actual answer, to the model for training. Later, the model will be given only the question, and with the help of available information on the web, it will obtain the final answer. The model also uses cross-lingual retrieval, where English articles can be used for augmentation to obtain the final answer.

The project is still under development. 

# Dataset:
1. AHD Arabic Healthcare Dataset
2. Arabic Medical Q&A Dataset
3. Arabic_medical_dialogue (colloquial)
4. AraHealth (colloquial, tweets)
5. MAQA
6. medinstruct-52k-arabic (MSQ)

