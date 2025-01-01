# Advanced Sentiment Analysis App with AI-Powered Insights

This project is a Streamlit application that analyzes customer reviews using sentiment analysis and provides detailed actionable insights powered by Generative AI. The app is designed to help businesses understand customer feedback, identify trends, and improve their products or services.

---

## Features

### Sentiment Analysis
- Analyze customer reviews to determine their sentiment (Positive, Negative, or Neutral).
- Display sentiment labels and confidence scores for each review.

### Data Visualization
- Tabular report of the analysis.
- Sentiment distribution visualized using bar charts.

### AI-Powered Insights
- Summarize review statistics, including total reviews and sentiment breakdown.
- Generate actionable insights, trends, and recommendations using Google Generative AI.

### User-Friendly Interface
- Input reviews directly or upload them for analysis.
- Interactive feedback messages to guide users.

---

## Prerequisites

### Software Requirements
- Python 3.7 or later
- Visual Studio Code (or any Python IDE)
- Internet connection (for Generative AI API)

### Python Libraries
- `streamlit`
- `transformers`
- `pandas`
- `google-generativeai`

---
### Requirments
- `streamlit==1.18.0`
- `transformers==4.27.4`
- `pandas==1.5.3`
- `google-generativeai==0.2.0`

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/advanced-sentiment-analysis.git
cd advanced-sentiment-analysis
```

### 2. Create a Virtual Environment
```bash
python -m venv venv
```
Activate the virtual environment:
- **Windows**: `venv\Scripts\activate`
- **Mac/Linux**: `source venv/bin/activate`

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Configure Generative AI API
Add your API key in the `app.py` file:
```python
genai.configure(api_key="YOUR_API_KEY")
```

---

## Usage

### Run the Application
```bash
streamlit run app.py
```

### Input Reviews
1. Enter reviews in the text area (one review per line).
2. Click **Analyze Sentiment**.

### View Results
- Sentiment analysis report (table and chart).
- Summary of positive, negative, and neutral reviews.
- AI-generated actionable insights and recommendations.

---

## Project Structure
- `app.py`: Main application script.
- `requirements.txt`: List of dependencies.

---

## Example Output
1. **Sentiment Analysis Report**:
   | Review                 | Sentiment | Confidence |
   |------------------------|-----------|------------|
   | "Great product!"       | Positive  | 0.98       |
   | "Not worth the price." | Negative  | 0.92       |

2. **Sentiment Distribution**:
   - Positive: 60%
   - Negative: 30%
   - Neutral: 10%

3. **AI-Powered Insights**:
   - "Customers appreciate the product quality but feel it is overpriced. Consider revising the pricing strategy."

---

## Contributing
1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Push to the branch.
5. Submit a pull request.

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Contact
For questions or feedback, please contact:
- **Name**: [Ashwin K.B.](mailto:your-email@example.com)
- **GitHub**: [Your GitHub Profile](https://github.com/your-username/)
