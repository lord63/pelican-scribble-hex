# Pelican-scribble-hex

A Pelican theme which was ported from [scribble][].

![demo-image][]

## How to use it

I assume that you've installed Pelican.

1. fork this repo and clone it, let's say we are under `/home/lord63/code/blog/`

        $ git clone git@github.com:USERNAME/pelican-scribble-hex.git

1. add `THEME` in your own `pelicanconf.py`

        THEME = '/home/lord63/code/blog/pelican-scribble-hex/'

1. copying other settings in the `pelicanconf_sample.py` to your own
`pelicanconf.py` and set them up

1. regenerate the blog using the new theme

        $ make html && make serve

1. open your browser: `127.0.0.1:8000` and have a check

## Credits

All the glories should belong to @muan, I just port it to Pelican :)

## License

MIT.

[scribble]: https://github.com/muan/scribble
[demo-image]: https://cloud.githubusercontent.com/assets/5268051/7243713/76c15be0-e803-11e4-81da-b7f406adc9cb.jpg
