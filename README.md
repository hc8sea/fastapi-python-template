[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fhc8sea%2Ffastapi-python-template&demo-title=FastAPI%20%2B%20Vercel&demo-description=Use%20FastAPI%20on%20Vercel%20with%20Serverless%20Functions%20using%20the%20Python%20Runtime.&demo-url=https%3A%2F%2Ffastapi-python-template.vercel.app%2F&demo-image=https://miro.medium.com/v2/resize:fit:640/1*dpXAaEpwsJcs2UbZEp5jJw.png)

# FastAPI + Vercel

This example shows how to use FastAPI on Vercel with Serverless Functions using the [Python Runtime](https://vercel.com/docs/concepts/functions/serverless-functions/runtimes/python).

## Demo

https://fastapi-python-template.vercel.app/

## How it Works

This example uses the Asynchronous Server Gateway Interface (ASGI) with FastAPI to enable handling requests on Vercel with Serverless Functions. For additional usage examples, refer to the [FastAPI repository](https://github.com/tiangolo/fastapi/).

## Running Locally

For macOS/Linux:

```bash
python3 -m venv venv
source venv/bin/activate
python3 -m pip install -r requirements.txt
python3 -m uvicorn api.index:app --reload
```

For Windows:

```bash
python -m venv venv
.\venv\Scripts\activate
python -m pip install -r requirements.txt
python -m uvicorn api.index:app --reload
```

Your FastAPI application is now available at `http://127.0.0.1:8000/`.

## API Documentation

Now go to `http://127.0.0.1:8000/docs`.

You will see the automatic interactive API documentation (provided by [Swagger UI](https://github.com/swagger-api/swagger-ui)):
Alternatively, go to `http://127.0.0.1:8000/redoc` to see the alternative documentaion (provided by [ReDoc](https://github.com/Rebilly/ReDoc)).

## One-Click Deploy

Deploy the example using [Vercel](https://vercel.com?utm_source=github&utm_medium=readme&utm_campaign=vercel-examples):

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fhc8sea%2Ffastapi-python-template%2Ftree%2Fmain&demo-title=FastAPI%20%2B%20Vercel&demo-description=Use%20FastAPI%20on%20Vercel%20with%20Serverless%20Functions%20using%20the%20Python%20Runtime.&demo-url=https%3A%2F%2Ffastapi-python-template.vercel.app%2F&demo-image=https://miro.medium.com/v2/resize:fit:640/1*dpXAaEpwsJcs2UbZEp5jJw.png)
