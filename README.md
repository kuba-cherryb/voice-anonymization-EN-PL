**Voice Anonymization**

Voice anonymizing models in English and Polish, made during a speech technology class as a group project in 2025.
The model is based on speech resynthesis (analysis - anonymization - synthesis) to tokenize his identity and
change it so that it's unrecognizable both empirically and by speaker recognition systems. It makes use of
pretrained models such as Whisper by OpenAI for linguistic analysis, SpeechBrain's spkrec-xvect-voxceleb for 
speaker embedding, and SpeechT5 of Microsoft as text-to-speech synthesizer with additional x-vector input.
Last model has also been fine-tuned to adapt for Polish speech. Anonymization has been achieved by geometic
transformations of the speaker embedding in x-vector hyperspace. 

![image](https://github.com/user-attachments/assets/f270089d-3223-413f-8a62-b3059cb9d0d0)

***Anonymization by maximal euclidian distance***
![image](https://github.com/user-attachments/assets/eee3575a-29dd-494b-9ddb-6f53e4324610)

***Anonymization by averaging three of the most distant vectors from database***
![image](https://github.com/user-attachments/assets/49408a2f-836b-4e27-b759-dc015bb01981)

***Anonymization by randomly choosing the output vector***
![image](https://github.com/user-attachments/assets/0c0c9904-f2ab-48eb-be22-67d3584c1a28)
