# Portfolio


## Projects
1. [Chess AI tutor](https://github.com/rschen5/ChessGPTutor)
2. [Social network simulation](https://github.com/rschen5/SimulatingSocialNetworks)
3. [Reward bot](https://github.com/rschen5/Piazza-Reward-Bot)
4. [Gaussian process emulator for the Greenland Ice Sheet](https://github.com/rschen5/rschen5-portfolio/tree/main/projects/gp-emulator)
5. [Image classification model](https://github.com/rschen5/rschen5-portfolio/tree/main/projects/image-classification)
6. [Linear regression model](https://github.com/rschen5/rschen5-portfolio/tree/main/projects/linear-reg-model)


### Chess AI tutor
Game AI project integrating ChatGPT into chess for move explanations with Stockfish as the engine. This project involved prompt engineering, which required tuning in order to configure the best way to return explanations. This was an interesting study into how ChatGPT interprets a game with clearly defined rules (and can make funny mistakes!). Check it out to play a chess game against a computer opponent!


### Social network simulation
A simple model for replicating user behavior in online social networks. The model includes various agents representing users, who interact with each other through creating, viewing, or liking posts. This was a great study looking into how users within social networks interact with others, migrate across networks, and affect/are affected by the beliefs, emotions, and sentiments of other users.


### Reward bot
Piazza is a popular platform that facilitates discussion between students and professors in a forum format. This bot reports personalized statistics and converts them into points that can be used by instructors to incentivize students and increase forum engagement. I primarily contributed to the data collection, storage, and statistics generation part of this bot. I implemented a scraper to collect and parse data from a Piazza forum, calculate participation points for each student, and update the points in a MongoDB database. I then automated the data collection and storage process with a daily job.


### Gaussian process emulator
In summer 2019, I worked on implementing a Gaussian process emulator with Dr. Andy Aschwanden at the University of Alaska Fairbanks to project sea level contribution from the Greenland Ice Sheet. Dr. Aschwanden previously worked on a [geophysical model](https://github.com/pism/pism-gris) to estimate contribution, but it was very computationally expensive and did not have a good way to quantify uncertainty. The emulator was able to project contribution with a 0.52 root mean square deviation.

Included is a presentation that I gave at the American Geophysical Union. The plots were made using matplotlib in Python.


### Image classification model
This is a group project I worked on for a class in Automated Learning and Data Analysis this semester. My group members and I used the Caltech-256 dataset (over 30k images in 256 categories) and implemented various learning methods, specifically Naive Bayes, K-Means clustering, and K-Nearest Neighbors.

Included is the final report and implementation (with Python). The data set can be found [on Kaggle](https://www.kaggle.com/jessicali9530/caltech256).


### Linear regression model
This is a group project I completed for a Regression Analysis class as an undergraduate. My group members and I built a linear regression model to predict carbon dioxide emissions from various factors related to the environment, health, and development of a country. The data is from the World Bank.

Included is the final report, implementation (with R), and data set used.
