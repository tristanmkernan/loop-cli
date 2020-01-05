# Loop Cli

The power of [loopifi](https://github.com/nyavramov/loopifi), in your hands.

## Setup

Make sure you have `ffmpeg` installed and in your `$PATH`.

Create a virtual environment:

```shell script
$ python3 -m venv env
$ source env/bin/activate
$ pip install -r requirements.txt
```

Run the script against your input `.mp4` video:

```shell script
$ python main.py sample.mp4
```

Find your generated loops in the `Loops/` folder next to your input video.

## License

MIT
