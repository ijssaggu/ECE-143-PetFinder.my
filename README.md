# ECE-143-PetFinder.my
We analyze data from PetFinder.my to determine how likely it is for a pet to get adopted and make further inferences.

*Data stored in the folder 'data' outside the working directory*

### data 
Contains .csv files used for labeling the data as well as the data itself (train.csv)

### Pet-Finder ECE143_Slides.pdf
Slides used for presentation as .pdf (to prevent formatting issues)

### State-wise_and_Recommender.ipynb (and utils_recommender.py)
Implementation of State-wise analysis, mainly,
- Correlating state-wise count with HDI
- Combining States based on HDI
- Average Adoption Rate per State (and new state)
- Recommender System for Pet Adoption
- utils_recommender.py contains all the necessary functions

### Age_Plots.ipynb (and .py)
Anaylysis of how age affects average adoption rate
- Shows distribution of cats and dogs at different ages
- Plots average adoption rate at different ages

### Gender_Color_Plots.ipynb (and .py)
Analysis of how gender and color affects average adoption rate
- Plots average adoption rate vs gender
- Plots average adoption rate vs color coat

### Type_BreedID_Analysis.ipynb (and .py)
Analysis of cat and dog distributions in top 4 states, maturity size, breed
- Maturity Size distributions per state
- Breed Distributions using WordCloud
- Maturity Size vs. Average Adoption Speed
- Adoption Speed Spread for Top 10 Breeds 

### Name visualization.ipynb (and .py)
Analysis of names for dogs and cats and correlation between health-related attributes
- WordCloud of top names for dogs and cats
- Plots/matrix demonstrating relationship between health attributes like deworming 
  and sterilization with average adoption speed
