## whiterspace

Another minimal theme for [Octopress](http://octopress.org) based on [whitespace](https://github.com/lucaslew/whitespace).

View the live theme [here](http://www.mherman.org).

### Install

```shell
$ cd octopress
$ git clone git://github.com/mjhea0/whiterspace.git .themes/whiterspace
$ rake install['whiterspace']
$ rake generate && rake deploy
```
    
### To do

1. Fix the damn search - help! <3
2. Add AddThis share buttons. Speaking of which ...

### Want to use AddThis share buttons?

Edit "/source/_includes/post/sharing.html" ...

```html
<div class="sharing">
<!--   {% if site.twitter_tweet_button %}
  <a href="http://twitter.com/share" class="twitter-share-button" data-url="{{ site.url }}{{ page.url }}" data-via="{{ site.twitter_user }}" data-counturl="{{ site.url }}{{ page.url }}" >Tweet</a>
  {% endif %}
  {% if site.google_plus_one %}
  <div class="g-plusone" data-size="{{ site.google_plus_one_size }}"></div>
  {% endif %}
  {% if site.facebook_like %}
    <div class="fb-like" data-send="true" data-width="450" data-show-faces="false"></div>
  {% endif %} -->
  <br>
  <!-- AddThis Button BEGIN -->
  <div class="addthis_toolbox addthis_default_style addthis_32x32_style">
  <a class="addthis_button_preferred_1"></a>
  <a class="addthis_button_preferred_2"></a>
  <a class="addthis_button_preferred_3"></a>
  <a class="addthis_button_preferred_4"></a>
  <a class="addthis_button_compact"></a>
  <a class="addthis_counter addthis_bubble_style"></a>
  </div>
  <script type="text/javascript">var addthis_config = {"data_track_addressbar":true};</script>
  <script type="text/javascript" src="//s7.addthis.com/js/300/addthis_widget.js#pubid=YOUR_ID_GOES_HERE"></script>
  <!-- AddThis Button END -->
  <br>
</div>
```

