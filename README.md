# Columbus-Blue-Jackets-Capstone-Project
**Transforming Qualitative Scouting Reports into Quantifiable Metrics**

Analytics and scouting reports provide a diverse set of insights for National Hockey League (NHL) player 
evaluation departments. However, they are treated as mutually exclusive analyses which need to be manually 
combined to create comprehensive player evaluations. 

The Columbus Blue Jackets requested an efficient methodology to assess the performance of players from a 
combined analytical and scouting report perspective. The team sought to create quantifiable scouting reports
metrics which could be seamlessly integrated into analytical models without compromising report integrity. This 
would create a massive competitive advantage for Columbus and can be adapted to any competitive sports 
industry around the world!


**The Solution: Valence Aware Dictionary for Sentiment Reasoning (VADER) Scores**

VADER scores considers the polarity and intensity of emotion within a group of text to quantify them into a 
compound score. The model is comprised of four sections:

1) String Processing: Scraping textual scouting reports into phrases and categorizing them based on four 
main skills (Character, Skating, Shooting, and Puck Skill).
2) Sentiment Analysis: Applying VADER scores on the phrases.
3) Sentiment Analysis Adjustment: Adjust VADER scores based on player archetypes and report source.
4) Final Quantitative and Qualitative Combination: Outputting finalized metric which can be combined with 
quantitative models and metrics.

The design process focused on modularity and a high level of user control. Modularity allows for easy 
reconfiguration of the model to generate diverse insights. User control allows manual adjustment of the scores 
to reflect team philosophies and trust in each scouting source. This allows for the scores to reflect the genuine 
sentiment of the scouting process by valuing the knowledge and expertise of scouts.
