# Simple rust health check

Simple health check rest api for [Rust](https://www.rust-lang.org/) using [actix-web](https://actix.rs/) framework


# Getting Started

##  Installation

  1. Clone the application
  ```
  git clone git@github.com:theipol/rust-health-check.git
  ```
  2. Build the application
  ```
  cargo build
  ```
  3. Run de application
  ```
  cargo run
  ```

## Usage

```http
GET /health
```
```http
CURL -i http://localhost:8080/health
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)


algo