# Amazon Price Tracker

This project is an Amazon Price Tracker that monitors the price of a specific product on Amazon. When the price drops below a certain threshold, the script sends an email notification using the `smtplib` library.

## Libraries Used

- **Beautiful Soup**: For parsing HTML and extracting data from the Amazon product page.
- **Requests**: To send HTTP requests and retrieve the content of the product page.
- **Pandas**: For data manipulation and saving the product price history to a CSV file.
- **smtplib**: To send email notifications when the product price drops below the specified threshold.

## Features

- Scrapes the current price of a specified product from Amazon.
- Compares the current price with a predefined threshold.
- Sends an email alert when the price drops below the threshold.
- Saves the price history to a CSV file for future reference.

## Purpose

This project was developed during my free time as a way to practice web scraping and data handling. It combines multiple libraries to create a practical tool that can be useful for anyone interested in monitoring product prices on Amazon.


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the authors of the libraries used in this project.
- Inspiration from various online tutorials on web scraping and email notifications.
