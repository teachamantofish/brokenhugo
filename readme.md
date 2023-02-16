# hugotest

If things aren't rendering on localhost:1313, do the following:

- Stop the Hugo server by pressing `CTRL` + `C`
- Ensure you're in the same folder as the `config.toml` file, then type the command `hugo` and hit enter. This rebuilds the entire project using the hugo build engine or whatever
- Then restart the Hugo server by typing the command `hugo server --disableFastRender`
