---
layout: default
title: How
description : How to install and run jekyll redirect from plugins.
permalink: /how
---

Download zip file on our repo 

[download jekyll from link →](https://github.com/mesinkasir/jekyll-redirect-link/archive/refs/heads/main.zip)

or clone the repo

`git clone https://github.com/mesinkasir/jekyll-redirect-link.git`

--------

Manual installation

Open your jekyll project and run 

`gem install jekyll-redirect-from`

or open Gemfile with code editor, then input this code :

```
group :jekyll_plugins do
  gem 'jekyll-redirect-from'
end
```

Now open `_config.yml` and insert plugins

```
plugins:
  - jekyll-redirect-from

whitelist:
  - jekyll-redirect-from

redirect_from:
  json: false
```

Next step: 

[implementation jekyll redirect form →](/implementation)
