# Power of YET - Blog


## To Deploy to Github Pages Site

1. In `_config.yml`, change (on lines 17:18), change from 

```python
# url: "https://esthercordova.github.io/powerofyet-blog/" # the base hostname & protocol for your site
url: "" # the base hostname & protocol for your site
```

to

```python
url: "https://esthercordova.github.io/powerofyet-blog/" # the base hostname & protocol for your site
# url: "" # the base hostname & protocol for your site
```

2. Build site (compiles static site into the `/_site` folder)

`bundle exec jekyll build`

3. Push to github 

```
git add .
git commit -m "awesome commit"
git push origin master
```

## To Run Site Locally 

1. In `_config.yml`, change (on lines 17:18), change from 

```python
url: "https://esthercordova.github.io/powerofyet-blog/" # the base hostname & protocol for your site
# url: "" # the base hostname & protocol for your site
```

to 

```python
# url: "https://esthercordova.github.io/powerofyet-blog/" # the base hostname & protocol for your site
url: "" # the base hostname & protocol for your site
```

2. Compile code and serve on localhost 

```
bundle exec jekyll serve --watch
```

3. Then navigate to [http://localhost:4000](http://localhost:4000)  to see the webpage 


## Some Site References

background-color: #FDDC66;
border-color: #d8bb51;
color: #4f482d;

