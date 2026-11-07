# FastAPI Health Check API

## About the Project
This is a simple Health Check API developed using Python and FastAPI.

It contains one endpoint that checks whether the API is running successfully.

## Technologies Used
- Python
- FastAPI
- Uvicorn
- Postman

## API Endpoint

**GET /health**

URL:
`http://127.0.0.1:8000/health`

Response:
```json
{
  "status": "ok"
}
```

## Installation Steps

1. Install Python.
2. Download or clone this repository.
3. Open the project folder in VS Code.
4. Install dependencies:

```bash
pip install -r requirements.txt
```

5. Start the server:

```bash
uvicorn main:app --reload
```

6. Open the API:

`http://127.0.0.1:8000/health`

## Testing
The API was tested using Postman and returned a successful 200 OK response.

## Note
This is a Docker-free development version. The API runs locally using Python and Uvicorn.
