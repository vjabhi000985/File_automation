# File Automation with Python

This project demonstrates automation of file and directory creation using Python. It includes a Python script that dynamically creates directories and empty files based on a predefined list.

## How it Works

The Python script utilizes the `os`, `pathlib`, and `logging` modules to automate the process. It iterates over a list of file paths, creates directories if needed, and then creates empty files if they don't exist or are empty.

## Project Structure

- `.github/workflows/.gitkeep`: GitHub Actions workflow directory placeholder.
- `src/notepad/__init__.py`: Initialization file for the main project.
- `src/notepad/components/__init__.py`: Initialization file for components.
- `src/notepad/utils/__init__.py`: Initialization file for utilities.
- `src/notepad/utils/common.py`: Common utility functions.
- `src/notepad/config/__init__.py`: Initialization file for configuration.
- `src/notepad/config/configuration.py`: Configuration module.
- `config/config.yaml`: Configuration file.
- `params.yaml`: Parameters file.
- `app.py`: Main application file.
- `main.py`: Entry point of the application.
- `Dockerfile`: Docker configuration file.
- `requirements.txt`: Python dependencies file.
- `setup.py`: Setup file for packaging.
- `research/reviews.ipynb`: Jupyter notebook for research or reviews.

## How to Use

1. Clone the repository.
2. Modify the `list_of_files` variable in the script to match your project's file structure if needed.
3. Run the script.
4. Check the created files and directories in your project.

## Dependencies

- Python 3.x

## License

This project is licensed under the [MIT License](LICENSE).
