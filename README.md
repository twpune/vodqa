## Local development

Check if you have [all requirements for local environment](http://jekyllrb.com/docs/installation/).
To install all development dependencies install [Bundler](http://bundler.io/).
```bash
    gem install bundler
```
and run next command from root folder:

```bash
  bundle install
```  

To start Jekyll run:
```bash
    jekyll serve -w
```
Site will be available at http://127.0.0.1:4000/vodqa/

**NOTE:** in this mode all changes to html and data files will be automatically regenerated, but after changing ```_config.yml``` you have to restart server.

For more details refer to https://github.com/gdg-x/zeppelin/

## How to update

The site can be updated by changing the ```_config.yml``` . For example, To change the main title we can simply change the `heroTitle: "VodQA 2021"` in ```_config.yml```.

Schedule and session details can be updated by modifying the `_data/schedule.yml`, `_data/sessions.yml` and `_data/speakers.yml`.

## About github hosting
The site is hosted against `master` branch and can be accessed by visiting https://twpune.github.io/vodqa/

Please refer to https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll.