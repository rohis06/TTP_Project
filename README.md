## Harmonies of the Mind: Investigating the Interplay Between Musical Preferences and Mental Well-being

### Introduction

Music therapy has gained attention as a promising intervention for enhancing mental health and well-being. By harnessing the therapeutic potential of music, music therapy offers a non-invasive and accessible approach to addressing mental health conditions. Research has demonstrated its effectiveness in improving mood, reducing stress, and promoting relaxation, making it a valuable adjunct to traditional psychotherapeutic interventions [1, 2]. Despite the growing recognition of music therapy’s benefits, there remains a gap in understanding how individual music preferences may influence its outcomes. Music is a deeply personal and subjective experience, with individuals gravitating toward specific genres, artists, and songs based on their unique preferences, backgrounds, and emotional associations. These preferences may not only reflect personal taste but also serve as coping mechanisms or sources of emotional resonance [3]. However, the relationship between music preference and mental health outcomes within the context of music therapy has been relatively underexplored [4]. While some studies have investigated the effects of specific music genres or styles on mood regulation and emotional well-being, few have examined how individual differences in music taste may impact the effectiveness of music therapy interventions. This report delves into the statistical analysis and modeling techniques used to explore these relationships, aiming to uncover insights into how music might affect mental well-being and the potential individual characteristics that could predict these effects.

### Background and Motivation

Music plays an important role in our daily routines, influencing activities like work, exercise, and relaxation. It significantly impacts mood and stress levels, making it a potential tool for emotional regulation. With rising mental health issues, it is crucial to explore music's effects on an individual's mental health. Understanding this interplay between music preference and mental well-being could have significant implications for the development of personalized interventions and the optimization of music therapy practices. By identifying which music genres or styles are most closely associated with positive mental health outcomes, clinicians and therapists may be better equipped to tailor their interventions to individual preferences, thereby enhancing engagement, efficacy, and client satisfaction. Motivated by this gap in research, our project aims to analyze the MxMH dataset available on Kaggle to uncover potential correlations between respondents' music preferences and self-reported mental health indicators.

With limited longitudinal data, we are unable to explore the treatment effects of music therapy on mental health conditions. Nonetheless, through rigorous data analysis and statistical modeling, we seek to explore the complex correlation between music preferences and mental well-being, ultimately contributing to the advancement of evidence-based practices in music therapy and mental health care.

### Research Questions

To systematically investigate the interplay between musical preferences and mental well-being, we have formulated three key research questions:

**RQ1: Besides streaming music, are “musicians” associated with better mental health conditions?** To address this question, we will compare the mental health conditions of musicians and non-musicians. Comparative testing approaches, including t-tests and Analysis of Variance (ANOVA), will be employed to determine if there are significant differences in mental health outcomes between these groups. 

**RQ2: What are the individual characteristics associated with mental well-being?** This question seeks to identify specific individual characteristics that correlate with mental well-being. We will perform regression modeling and inferential analysis using various feature selection techniques to pinpoint the most influential factors. 

**RQ3: Can individual characteristics predict the music effects? If so, how accurately?** The final research question explores the predictive power of individual characteristics on the effects of music. Using advanced machine learning models such as Linear Discriminant Analysis (LDA), Random Forest, and Neural Networks, we will assess the accuracy of these predictions. 

Our project contributed the following findings:

- Provided a comprehensive insight of the dataset, identifying early patterns and trends between potential predictors and response variables through detailed exploratory data analysis.
- Used stepwise modeling in data preprocessing phase to predict missing values for beats per minutes (BPM) of respondent favorite genre without affecting the multicollinearity aspect of the model.
- Comparative analysis suggested no statistical difference between musicians and non-musicians.
- Inferential modeling revealed that different favorite music genres and listening frequencies are associated with different mental health conditions.
- Generalized Additive Modeling explored the non-linear relationship between age and hours of listening to music per day and levels of mental health.
- Predictive modeling assessed the effectiveness of individual characteristics in the dataset in predicting music effectiveness on mental health.
