# Trademarkia
Class Recommendation System (K-Nearest Neighbour) AI Engineer Task

the development of an AI model to suggest trademark classifications based on the user-entered products and services. The code makes use of the dataset from the USPTO ID Handbook and presents a REST API for interoperability with the Flask framework.


The /recommend route is now capable of handling both GET and POST queries. Recommendations are returned in response to GET requests, whereas POST requests cause the class suggestion to be made depending on the supplied information about the goods and services.

Keep in mind to start the programme by typing python trademarkia-recommendation.py after saving the code in a Python file. When the Flask server is up and running, you can test sending a POST request to http://localhost:5000/recommend with the recommended trademark classes in the request body as JSON.
