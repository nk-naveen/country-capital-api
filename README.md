
# Country-capital-api
The Country Capital API is a simple API written in Python and Flask that allows you to retrieve the name of a country based on a provided capital city. The API is served using the ASGI server Uvicorn, and can be accessed via a microservice endpoint at https://example.com/country-capital/<query-params>.
### Installation
To install the necessary dependencies for this API, you can use pip to install the requirements.txt file included in the repository:
```bash
pip install -r requirements.txt
```
### Usage
To start the API, you can run the following command:
```bash
uvicorn app:app
```
This assumes that your Flask app is defined in a Python file called app.py, and that the Flask app object is called app. Uvicorn will start the server on http://localhost:8000 by default. To use the microservice endpoint for this API, you can make HTTP GET requests to https://example.com/country-capital/<query-params> with the appropriate query parameters. The <query-params> placeholder should be replaced with the appropriate query parameter for your API. For example, to retrieve the name of the country with the capital city "Paris", you can make an HTTP GET request to https://example.com/country-capital/?capital_city=Paris.
### License
The Country Capital API is licensed under the [MIT License.](https://choosealicense.com/licenses/mit/) 
