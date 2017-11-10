# !!! Don't use this version. This is only to archive this files !!!


# [luftdaten.info](http://luftdaten.info/) [![Build Status](https://travis-ci.org/opendata-stuttgart/luftdaten.info.svg)](https://travis-ci.org/opendata-stuttgart/luftdaten.info)

## Local builds

1. Create development environment

  1. Clone [git](http://git-scm.com/) repository

    ```
    git clone https://github.com/opendata-stuttgart/luftdaten.info.git
    ```

  2. Install [Ruby](https://www.ruby-lang.org/en/downloads/) `>= 1.9.3`

  3. Install [Bundler](http://bundler.io/)

    ```
    gem install bundler
    ```

  4. Install [Jekyll](http://jekyllrb.com/)

    ```
    bundle install
    ```

2. Run Jekyll

  ```
  bundle exec jekyll serve
  ```

3. Open [`http://localhost:4000/`](http://localhost:4000/) in your browser
