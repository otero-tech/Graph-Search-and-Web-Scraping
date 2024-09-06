# Graph Search and Web Scraping Project

## Project Overview

This project focuses on implementing various search algorithms and web scraping techniques using Python. The primary objective is to practice inheritance, graph traversal, file handling, and web crawling. The project is structured into several parts, each building on the previous one, culminating in a final function that interacts with a web application.

### Key Components

1. **GraphSearcher Class**: A base class implementing Depth-First Search (DFS) and Breadth-First Search (BFS) algorithms, providing foundational graph traversal methods.

2. **MatrixSearcher Class**: Inherits from `GraphSearcher` to enable DFS and BFS on matrices represented as DataFrames.

3. **FileSearcher Class**: Extends `GraphSearcher` to traverse files within a directory, reading content, and managing file relationships.

4. **WebSearcher Class**: Utilizes Selenium to perform web scraping by visiting URLs, extracting linked pages, and compiling table data into a consolidated DataFrame.

5. **reveal_secrets Function**: Automates interactions with a web application by generating passwords, navigating the interface, and retrieving a location image.

### Installation

To run the project, ensure you have Python 3 installed along with the necessary libraries:

```bash
pip install selenium==4.1.2 Flask lxml html5lib pandas
