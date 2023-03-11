# markdown-cv

CV-as-code for Philip Wood
[CV Online](https://philipstaffordwood.github.io/philipstaffordwood-cv/)

A curriculum vitae maintained in plain text and rendered to HTML and PDF using CSS.

Initially Cloned from [sharu725/online-cv](https://github.com/sharu725/online-cv)

Based on Orbit (with customisations)
> This theme is designed by Xiaoying Riley at [3rd Wave Media](http://themes.3rdwavemedia.com/). 
> Visit her [website](http://themes.3rdwavemedia.com/) for more themes.

# Local Development and Editing

Clone repo:

```bash
git clone git@github.com:philipstaffordwood/philipstaffordwood-cv.git
cd philipstaffordwood-cv
```

Run a local Jekyll docker instance:

```bash
docker run --rm   --volume="$PWD:/srv/jekyll" -p 4000:4000  -it jekyll/jekyll:$JEKYLL_VERSION   jekyll serve
```
Preview available locally at [`http://localhost:4000/philipstaffordwood-cv/index.html`](http://localhost:4000/philipstaffordwood-cv/index.html)


## License

This project is licensed under the [MIT license](LICENSE.txt).

With the notable exclusion of the actual CV content contained in the [`_data/data.yml`] file which is fully copyrighted to Philip Wood:

Copyright &copy; 2020 Philip Wood All rights reserved
