# Digital Garden

Creating a basic CLI tool to take notes.

## Commands

### Setting the garden path

```sh
GARDEN_PATH=~/github/my-digital-garden write
garden -p ~/github/my-digital-garden write
garden --garden_path ~/github/my-digital-garden write
```

### Write

Open the default editor and save a file to your GARDEN_PATH:

```sh
garden write
garden write -t "Title string"
```

### Testing

For a singe test run, execute

```sh
cargo test
````

To keep the tests watching and execute on changes, run

```sh
cargo watch -x check  -x test
````
