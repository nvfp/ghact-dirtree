GitHub action for viewing a readable directory tree and also includes size for each file and folder.

## usage

```yml
name: ...
on: ...
jobs:
  ...:
    runs-on: ubuntu-latest
    steps:
      ...
      - uses: nvfp/ghact-dirtree@main
        with:
          dir: ./foo  # can be relative to root, and an abs. path.
          level: 3  # starts from 0. `null` for infinite.
```

Learn more about [the params here](https://github.com/nvfp/ghact-dirtree/blob/main/action.yml).

## License

MIT License. Feel free to use the code. Have a great day!
