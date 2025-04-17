# Linear Regression API

A simple Flask API to serve a linear regression model.

## Local Setup

1. Install dependencies:
```
pip install -r requirements.txt
```

2. Run the app:
```
python app.py
```

## API Usage

### GET /
Returns a simple message to confirm the API is running.

### POST /predict
Makes a prediction using the linear regression model.

Example request:
```
curl -X POST http://localhost:5000/predict \
-H "Content-Type: application/json" \
-d '{"features": [5.3]}'
```

Replace `5.3` with your own value for prediction. 