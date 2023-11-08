# varwwwhtml

varwwwhtml is a lightweight Python module that provides a simple HTTP server for serving static files. It offers an easy-to-use solution for quickly hosting static web content locally. Whether you're developing a small web application or need a temporary server for testing purposes, varwwwhtml has got you covered.

## Key Features
- Simple and intuitive HTTP server for static files
- Lightweight and easy to install
- Minimal dependencies
- Compatible with Python 3.x

## Installation
You can install varwwwhtml via pip, which is the recommended method:

```bash
pip install varwwwhtml
```

## Usage
To start serving your static files, follow these steps:

1. Open a terminal and navigate to the folder where your static project is located.
2. Run the following command:

```bash
python -m varwwwhtml
```

or

You can add cli arguments up to your usage

```bash
CLI tool that allows you to serve your static web app.

options:
  -h, --help            Show this help message and exit
  --host HOST           Host to serve on
  --port PORT           Port to serve on
  --path PATH           Path where static files in
  --search-for          File to search for if path is a directory
```

The server will start running, and you can access your static content by opening a web browser and entering the server's URL.
