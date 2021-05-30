## Transformer Chatbot

The proposed project aims to create a **generative model for Conversational AI agents**, limited to the language English. The agent must be able to comprehend the input statement and generate close-to-human responses for single-turn and multi-turn dialogue.<br />
It aims to aid people with their mental health issues, hence acting as a **TherapyBot**.

The proposed Conversational agent is meant to operate within the **psychological space** adhering to the following: 
 - Quick response generation
 - Context relevant responses
 - Grammatically correct responses
 
 Tensorflow 2.0 has been used for this usecase.
 
 ### Datasets used:
  1. [Facebook Data:](https://drive.google.com/file/d/1HoQCutYAlxqcaQg2WRhuhwy3JoKTJE77/view?usp=sharing)<br />
     This is an opensource dataset comprising of many open domain conversations of about 5-6 sentences, which make up for 58881 input-output pairs.

  2. [CounselChat Data:](https://drive.google.com/file/d/16SkmBtX_ikILD2fyh2k1k1VN8GQgsPjH/view?usp=sharing)<br />
     This includes 2130 therapist-client QnA scraped from counselchat.com, covering over 31 different topics ranging from ‘depression’ to ‘military issues’.
     
### Saved Model Weights:
The best performing model weights can be found [here](https://drive.google.com/file/d/1nTk24QbrpknghAIOhSq3cLacOGpnRsok/view?usp=sharing) and index file [here](https://drive.google.com/file/d/1Yg5R_KaXr4pknYHS_ILC3wTk_eopTpZA/view?usp=sharing).

### Evaluation Metrics:
  1. Loss
  2. Perplexity

