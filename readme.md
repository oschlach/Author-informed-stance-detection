# Dataset Data Dictionary

Below is the data dictionary describing the fields in the dataset.

![Data Dictionary Reference](image_c10a6a.png)

| Field | Meaning |
| :--- | :--- |
| user_id | Twitter user ID |
| political_confidence | SocialVec political confidence score [0,1] |
| political_label | SocialVec political affiliation prediction |
| SocialVec_len_political | Number of followee accounts the prediction is based on |
| tweet | Authored tweet |
| target | The target of the authored tweet |
| chatgpt_prompt_pred | Initial prediction of LLM |
| chatgpt_prompt_pred_explanation | Initial prediction of LLM self-explained |
| chatgpt_tweet_pred_final | Final (post chain of thought) stance prediction of LLM |
| chatgpt_author_pred_final | Final (post chain of thought) author prediction of LLM |
| mentions | Extracted mentions from tweet |
| hashtags | Extracted hashtags from tweet |
| explicit_target | Technical field |
| record_id | Index in original table |
| HIT_id | Amazon mechanical turk HIT ID - stance prediction non informed |
| all_answers_q1 | The set of the answers provided by the annotators - is the stance sarcastic |
| count_popular_answer_q1 | Frequency of the most popular annotation |
| all_answers_q2 | The set of the answers provided by the annotators - is the stance in favor or against the target |
| count_popular_answer_q2 | Frequency of the most popular annotation |
| all_answers_q3 | The set of the answers provided by the annotators - political affiliation of the author |
| count_popular_answer_q3 | Frequency of the most popular annotation |
| maj_vote_sarcasm | Majority vote result on sarcasm question |
| maj_vote_tweet | Majority vote result on stance question |
| maj_vote_author | Majority vote result on author affiliation question |
| HIT_id_author_info | Amazon mechanical turk HIT ID - stance prediction author informed |
| all_answers_q1_author_info | The set of the answers provided by the annotators - is the stance sarcastic |
| count_popular_answer_q1_author_info | Frequency of the most popular annotation |
| all_answers_q2_author_info | The set of the answers provided by the annotators - is the stance in favor or against the target |
| count_popular_answer_q2_author_info | Frequency of the most popular annotation |
| maj_vote_sarcasm_author_info | Majority vote result on sarcasm question |
| maj_vote_tweet_author_info | Majority vote result on stance question |
| maj_vote_tweet_author_info_einat | Majority vote - self annotation |
| data_source | Data subset (conflict\non-conflict between author affiliation and LLM predicted stance) |