# IPL Win Predictor

The IPL Win Predictor is a machine learning-based web application built using Streamlit, which predicts the probabilities of a batting team winning in an ongoing IPL match based on various match factors. It leverages a trained model to give win probabilities based on input such as the teams involved, the city, current score, number of overs, wickets, and the target score.

## Features

- Select the batting team, bowling team, and host city from a list.
- Input the target score, current score, overs completed, and wickets fallen.
- Predict the probabilities of the batting team and the bowling team winning the match.
- Provides real-time probability predictions when the "Predict Probabilities" button is clicked.

## Technologies Used

- **Streamlit**: For creating the web app.
- **Pickle**: To load the pre-trained model and necessary datasets.
- **Pandas**: For data manipulation.
- **Machine Learning Model**: The model used is trained to predict win probabilities based on match conditions.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/ipl-win-predictor.git
   cd ipl-win-predictor
2. Install the required libraries:

   ```bash
   pip install -r requirements.txt
3.Ensure the following files are present in the repository:
4.Run the Streamlit app:
  ```bash
  streamlit run app.py
 ```
# IPL Winning Probability Predictor

## Usage

1. Launch the app in your browser.
2. Select the batting team, bowling team, and host city.
3. Enter the target score, current score, overs completed, and wickets fallen.
4. Click the "Predict Probabilities" button to see the winning probabilities for the batting and bowling teams.

### Example:

**Input**
- Batting Team: Mumbai Indians
- Bowling Team: Chennai Super Kings
- Host City: Mumbai
- Target Score: 180
- Current Score: 120
- Overs Completed: 15
- Wickets Fell: 3

**Output**
- Mumbai Indians - 65%
- Chennai Super Kings - 35%

## WorkFlow:
![Screenshot (6)](https://github.com/user-attachments/assets/851d25ea-4cb4-427a-bb81-097ea9848398)
![Screenshot (7)](https://github.com/user-attachments/assets/d01f69cb-dd8a-4fdc-b0eb-3e74103aeb08)
![Screenshot (8)](https://github.com/user-attachments/assets/98bab46a-d983-47a1-9022-57a7b468ba9a)
![Screenshot (9)](https://github.com/user-attachments/assets/48536db5-68d0-4bf6-9cb6-34e2326398ea)




## Files

- `app.py`: The main Streamlit app file.
- `team.pkl`: Contains the data for IPL teams.
- `city.pkl`: Contains the data for IPL cities.
- `model.pkl`: Trained machine learning model to predict win probabilities.
- `requirements.txt`: Python dependencies required to run the app.

## Acknowledgements

- The dataset for IPL teams and cities.
- Machine learning model trained using historical IPL data.
