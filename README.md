# Confidence-Level-Estimation-System
Confidence Level Estimation System make use of AI to estimate the confidence level of a human by analyzing various parameters, the verbal and non-verbal cues that contribute some weightage while judging **human confidence**.
The designed model considers 3 parameters:
1. **Facial Expression**
2. **Eye Movement**
3. **Face Direction**

The input to the model is an interview video consisting a candidate, the model processes the video by dividing it into constant number of **frames** considering the video duration. The frames will be filtered out based on where the candidate face is present into the frame or not using **face detection**. This will help to **optimize**. Further the **Facial Expression Recognition, Eye Movement Detection and Face Direction Recognition** will be performed to extract the features. Based on the training, the model will estimate whether the candidate was **confident** or was **unconfident** in that particular frame. The results of all the frames will be analyzed to calculate the **confidence percentage**. Based on confidence percentage the **Confidence Level** will be decided as **High/Medium/Low**. The output(confidence level) and model analysis(Dominant Facial Expression, Dominant Eye Movement and Dominant Face Direction) will be downloaded in the form of a PDF.
This model finds its **application** in decision making systems like interviews and question-answering systems.
