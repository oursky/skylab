# Skylab.ai Landing Page Template
Using _Airspace_ for Jekyll
![screenshot](screenshots/home.png "Skylab preview")

## Structure

* Main Page
* Posts


## Steps for Setup:

### Make sure you have Ruby

First, make sure you have [Ruby](https://www.ruby-lang.org/en/) installed. You can confirm this by running `ruby -v` on the command line:

```sh
$ ruby -v
ruby [version number] (date) [your platform]
```

If you get something like `"Error, command not found"` visit the link above and install Ruby for your platform.


### Make sure you have Jekyll

Next, make sure you have [Jekyll](https://jekyllrb.com/) installed. Just like above, run `jekyll -v` on the command line:

```sh
$ jekyll -v
jekyll [version number]
```
If you get `"Error, command not found"` run `gem install jekyll` to install it using RubyGems.

### Run this repository
Clone the repository, and `cd` into it:
```sh
$ git clone https://github.com/ndrewtl/airspace-jekyll.git
$ cd airspace-jekyll
```

Install Dependencies:
```sh
$ bundle install
```

And run the server:
```sh
$ jekyll serve
```

### Contact form email

Email is sent using zapier webhook -> AWS Simple Email Service (SES)

### Attribution
This Jekyll theme is a port of ThemeFisher's Airspace template. It is released under ThemeFisher's free license, which requires attribution.