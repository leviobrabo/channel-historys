
# Telegram Historical Bot

This project is a Telegram bot designed to fetch and display historical data and events. It supports multiple features such as fetching historical images, events, and other related data. The bot is built using Python and leverages several libraries to manage data retrieval and processing.

## Features

- **Historical Data Fetching:** Retrieves historical data such as events, birthdays, and other relevant information.
- **Image Handling:** Supports fetching and processing historical images.
- **Logging and Configuration:** Well-structured logging and configuration files to manage the bot's operations.

## Project Structure

- `data/`: Directory containing the data files.
- `history/`: Contains scripts to update and manage historical data.
- `imgs/`: Stores images used or fetched by the bot.
- `.gitignore`: Git ignore file for excluding unnecessary files.
- `Procfile`: Configuration file for deploying on Heroku.
- `README.md`: Project documentation.
- `bot.conf`: Main configuration file for the bot.
- `bot.py`: Core bot logic and event handling.
- `db.py`: Database interaction script.
- `get_historical.py`: Script for fetching historical data.
- `logger.py`: Handles logging across the application.
- `main.py`: Main entry point for running the bot.
- `requirements.txt`: Python dependencies required for the project.
- `sample.bot.conf`: Sample configuration file for reference.

## How to Use

1. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

2. **Configure the bot:**
   - Edit the `bot.conf` or use the `sample.bot.conf` to set up your bot's configuration.

3. **Run the bot:**
   ```bash
   python main.py
   ```

## Contributing

Contributions are welcome! Feel free to submit pull requests, report issues, or suggest improvements.

## License

This project is licensed under the MIT License.
