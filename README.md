# Cache Replacement Algorithms

## Overview

This project demonstrates the implementation of various cache replacement algorithms using Python and Redis. The cache replacement algorithms implemented in this project are:

- **FIFO (First-In, First-Out)**
- **LIFO (Last-In, First-Out)**
- **LRU (Least Recently Used)**
- **MRU (Most Recently Used)**
- **LFU (Least Frequently Used)**

Each algorithm determines which cache entry should be removed when the cache reaches its capacity and a new item needs to be added.

## Project Structure

The project is organized as follows:

```graphql
cache-replacement-algorithms/
│
├── docker-compose.yml       # Docker Compose file to set up Python and Redis containers
├── Dockerfile               # Dockerfile for the Python application
├── app/
│   ├── main.py              # Main script to run the caching algorithms
│   ├── requirements.txt     # Python dependencies
│   ├── fifo_cache.py        # FIFO cache algorithm implementation
│   ├── lifo_cache.py        # LIFO cache algorithm implementation
│   ├── lru_cache.py         # LRU cache algorithm implementation
│   ├── mru_cache.py         # MRU cache algorithm implementation
│   ├── lfu_cache.py         # LFU cache algorithm implementation
├── data/
└── redis/
    └── redis.conf           # Redis configuration file (if needed)
```

## Usage

To use this project, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/username/repository.git
    ```

2. Navigate to the project directory:

    ```bash
    cd cache-replacement-algorithms
    ```

3. Set up the Docker containers using Docker Compose:

    ```bash
    docker-compose up -d
    ```

4. Install the Python dependencies:

    ```bash
    pip install -r app/requirements.txt
    ```

5. Run the main script to execute the cache replacement algorithms:

    ```bash
    python app/main.py
    ```

6. Observe the output to see the cache replacement behavior for each algorithm.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements

This project was inspired by the need to understand and compare different cache replacement algorithms. Special thanks to the contributors and maintainers of the Python and Redis projects.
