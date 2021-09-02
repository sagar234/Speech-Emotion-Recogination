# Speech-Emotion-Recognition

# Introduction 

**Emotions play an important role in everyday human interaction. This is essential for your rational as well as intelligent decisions. By expressing your feelings and giving feedback to others, it helps to match and understand the feelings of others. Research has revealed the effective role of emotions in shaping human social interactions. Emotional displays provide significant information about a person's mental state.
Speech cues can usually be obtained more easily and economically. That is why the majority of researchers are interested in recognizing speech emotion (SER). The purpose of SER is to identify the underlying emotional state of the speaker from her voice. The interest in research in this field has increased in recent years**



![image](https://user-images.githubusercontent.com/74303124/129658636-2ee0967b-c136-4a52-9301-783dc6dea2bf.png)

# Problem Statement  

**Verbal Communication is valuable and sought after in workplace and classroom environments alike. There is no denying the notion that Indians lack verbal communication and consequently lag in the workplace or classroom environments. This happens despite them having strong technical competencies. Clear and comprehensive speech is the vital backbone of strong communication and presentation skills. Where some occupations consist mainly of presenting, most careers require and thrive from the ability to communicate effectively. 
Research has shown that verbal communication remains one of the most employable skills in both the perception of employers and new graduates. Of the possible improvements to vocal presentations tone, disfluencies, and stutters, in particular, remain one of the most common and prominent factors of someone’s demonstration. Millions of people are affected by stuttering and other speech disfluencies, with the majority of the world having experienced mild stutters while communicating under stressful conditions.
 Research shows that mild disfluencies can be cured without medical help, just practicing speech regularly and constructive feedbacks are effective ways to improve. We, Data Scientists recognize this problem and say hello.**
 
 # Dataset Information
 
 **The RAVDESS is a validated multimodal database of emotional speech and song. The database is gender balanced consisting of 24 professional actors, vocalizing lexically-matched statements in a neutral North American accent. Speech includes calm, happy, sad, angry, fearful, surprise, and disgust expressions, and song contains calm, happy, sad, angry, and fearful emotions. Each expression is produced at two levels of emotional intensity, with an additional neutral expression. All conditions are available in face-and voice, face-only, and voice-only formats.**
 
**The set of 7356 recordings were each rated 10 times on emotional validity, intensity, and genuineness. Ratings were provided by 247 individuals who were characteristic of untrained research participants from North America. A further set of 72 participants provided test-retest data. High levels of emotional validity and test-retest intrarater reliability were reported. Corrected accuracy and composite "goodness" measures are presented to assist researchers in the selection of stimuli. All recordings are made freely available under a Creative Commons license and can be downloaded at https://www.kaggle.com/uwrfkaggler/ravdess-emotional-song-audio**

# Dependencies
**Python**

**numpy**

**pandas**

**matplotlib**

**Pillow**

**opencv-python-headless**

**plotly**

**requests**

**librosa**

**streamlit**

**tensorflow-cpu**

**keras**

# Some Audio track 

![HAPPY](https://user-images.githubusercontent.com/74303124/129659965-1403187b-e752-48ea-8ad6-15642aa969e0.png)




![FEAR](https://user-images.githubusercontent.com/74303124/129660006-c7bf449a-ff6e-447c-8722-a94927d3eb8c.png)

# Spectrogram
![MALE NEUTRAL](https://user-images.githubusercontent.com/74303124/129660201-1aed9b15-e1dd-431e-a0db-baed5bcbc4c7.png)


# Buildings Model 

**since the project is a classification problem, Convolution Neural Network seems the obvious choice. We also built Multilayer perceptrons models but they under-performed with very low accuracies which couldn't pass the test while predicting the right emotions.**

![TRAIN LOSS TRAIN ACCURACY](https://user-images.githubusercontent.com/74303124/129661002-e87aa3c0-7db0-44b7-8a58-508446094c1e.png)


# Challenges

**Large speech Dataset to handle**

**Annotating an audio recording is challenging. Should we label a single word , sentence or a whole conversation? How many emotions should we define to recognize**


**It is not an easy task to convert speech to emotion**


**Emotions are subjective, people would interpret it differently. It is hard to define the notion of emotions**


# Conclusion 

**That's it! We come to the conclusion of our exercise. Starting with stacking the information so distant we have done EDA, Data  augmentation , Feature Extraction, and after that model building. we appeared how we will use Machine learning to get the basic feeling from speech sound information and a few bits of knowledge on the human expression of feeling through voice. This framework can be utilized in a assortment of setups like Call Middle for complaints or promoting, in voice-based virtual collaborators or chatbots, in phonetic inquire about, etc.** 





