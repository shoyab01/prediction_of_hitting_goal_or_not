# prediction_of_hitting_goal_or_not
Given data of the situation of the football matches with many details. Aim is to predict whether in the given situation, Ronaldo can score a goal or not?

Given many features as type of match (FIFA, league etc.), Opposition team, location kick, power of hit, remaining time of match etc.
To predict whether Ronaldo will hit the goal or not. Hitting the goal means 1 in is_goal attribute, otherwise 0.

# Evaluation Criteria

##### ϵ=1/MAE+1

MAE : Mean Absolute Error

Our main goal is to reduce MAE and I have done it.

# Competition Details

This competition was held only for IIITDM Kurnool students. The link for the competition is  
   
   https://www.kaggle.com/c/google-ai-iiitdm/
    
# Results

I trained the model using XGBClassifier and gained the following best result as:

    MAE = 0.37314
    
You can check my(Shoyab Azmal) results from the following link (in Public Leaderborad):
    
   https://www.kaggle.com/c/google-ai-iiitdm/leaderboard

And also check my overall submissions from the link:

   https://www.kaggle.com/c/google-ai-iiitdm/submissions
