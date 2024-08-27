# Project Overview  

TikTok users have the ability to report videos and comments that contain user claims. These reports identify content that needs to be reviewed by moderators. This process generates a large number of user reports that are difficult to address quickly. 

I have built Randon Forest and XGBoost models to determine whether a video contains a claim or offers an opinion. With a successful prediction model, TikTok can reduce the backlog of user reports and prioritize them more efficiently.  

Attributes:  
 1   claim_status              
 2   video_id                  
 3   video_duration_sec        
 4   video_transcription_text  
 5   verified_status           
 6   author_ban_status         
 7   video_view_count          
 8   video_like_count          
 9   video_share_count         
 10  video_download_count      
 11  video_comment_count  

 Key insights from EAD:  Both models RF and XGB performed well. The RF model had a better recall score. performance on the test holdout data yielded near perfect scores, with only five misclassified smaples out of 3,817.  
