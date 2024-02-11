# NShorts

NShorts is a Python Flask web application that utilizes the News API to provide users with the latest news articles. Users can search for news articles by providing keywords and can also filter articles by news source and category.

## Features

- **Search:** Users can search for news articles by entering keywords.
- **Filter:** Users can filter articles by news source and category.
- **Latest News:** Provides users with the latest news articles fetched from the News API.
- **Responsive Design:** The web application is designed to be responsive and work seamlessly across different devices.

## Technologies Used

- **Python:** Flask is used as the web framework.
- **News API:** Fetches news articles from various sources.
- **HTML/CSS:** Frontend is designed using HTML and CSS for styling.
- **JavaScript:** Some frontend interactions and AJAX requests are handled using JavaScript.
  
## Usage

To use this application, follow these steps:

1. Clone this repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Obtain a News API key from [News API](https://newsapi.org/) and replace the placeholder in the `config.py` file with your API key.
4. Run the application using `python app.py`.
5. Access the application in your web browser at `http://localhost:5000`.

## Contributing

Contributions are welcome! If you would like to contribute to this project, feel free to fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to [News API](https://newsapi.org/) for providing the news articles.
- This project was inspired by the need for a simple and intuitive news aggregator.
