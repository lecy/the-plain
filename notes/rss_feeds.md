
## Custom Javascript

http://blog.emmatosch.com/2016/03/09/using-custom-javascript-in-jekyll-blogs.html


# Feed Reader Generator:

https://feed.mikle.com/?gclid=CMCOjPbrhKUCFQNY2godQ14IPw


THIS ONE !!!
```
<script type="text/javascript" src="https://feed.mikle.com/js/fw-loader.js" data-fw-param="25490/"></script>
```

From:

https://www.sitepoint.com/community/t/how-to-add-an-rss-feed-from-bbc-news-to-my-site/6693




<iframe src="https://feed.mikle.com/widget/v2/25490/"></iframe>




# Google RSS Feed Widget:

http://www.developerdrive.com/2012/03/a-simple-way-to-add-free-news-content-to-your-website/

```
<script type="text/javascript" src="https://www.google.com/jsapi"></script>
<script src="http://www.google.com/uds/solutions/dynamicfeed/gfdynamicfeedcontrol.js"
type="text/javascript"></script>

<style type="text/css">
@import url("http://www.google.com/uds/solutions/dynamicfeed/gfdynamicfeedcontrol.css");

#feedControl {
margin-top : 10px;
margin-left: auto;
margin-right: auto;
width : 440px;
font-size: 12px;
color: #9CADD0;
}
</style>
<script type="text/javascript">
function load() {
var feed ="http://feeds.bbci.co.uk/news/world/rss.xml";
new GFdynamicFeedControl(feed, "feedControl");

}
google.load("feeds", "1");
google.setOnLoadCallback(load);
</script>
```

```
<div id="body">
<div id="feedControl">Loading...</div>
</div>
```


## RSS Feed Reader Widgets

Generate a free feed widget here:  http://www.surfing-waves.com/feed.htm

```
<!-- start sw-rss-feed code --> 
<script type="text/javascript"> 
<!-- 
rssfeed_url = new Array(); 
rssfeed_url[0]="https://groups.google.com/forum/feed/irs-990-collaborative-shared-group-space/msgs/rss.xml?num=15";  
rssfeed_frame_width="400"; 
rssfeed_frame_height="250"; 
rssfeed_scroll="on"; 
rssfeed_scroll_step="6"; 
rssfeed_scroll_bar="off"; 
rssfeed_target="_blank"; 
rssfeed_font_size="12"; 
rssfeed_font_face=""; 
rssfeed_border="on"; 
rssfeed_css_url="http://feed.surfing-waves.com/css/style4.css"; 
rssfeed_title="on"; 
rssfeed_title_name=""; 
rssfeed_title_bgcolor="#3366ff"; 
rssfeed_title_color="#fff"; 
rssfeed_title_bgimage="http://"; 
rssfeed_footer="off"; 
rssfeed_footer_name="rss feed"; 
rssfeed_footer_bgcolor="#fff"; 
rssfeed_footer_color="#333"; 
rssfeed_footer_bgimage="http://"; 
rssfeed_item_title_length="50"; 
rssfeed_item_title_color="#666"; 
rssfeed_item_bgcolor="#fff"; 
rssfeed_item_bgimage="http://"; 
rssfeed_item_border_bottom="on"; 
rssfeed_item_source_icon="off"; 
rssfeed_item_date="off"; 
rssfeed_item_description="on"; 
rssfeed_item_description_length="120"; 
rssfeed_item_description_color="#666"; 
rssfeed_item_description_link_color="#333"; 
rssfeed_item_description_tag="off"; 
rssfeed_no_items="0"; 
rssfeed_cache = "b40796d04d08a7d46b2ef794a786e760"; 
//--> 
</script> 
<script type="text/javascript" src="http://feed.surfing-waves.com/js/rss-feed.js"></script> 
<!-- The link below helps keep this service FREE, and helps other people find the SW widget. Please be cool and keep it! Thanks. --> 
<div style="text-align:right; width:400px;"><a href="http://www.surfing-waves.com/feed.htm" target="_blank" style="color:#ccc;font-size:10px">widget @</a> <a href="http://www.surfing-waves.com" target="_blank" style="color:#ccc;font-size:10px">surfing-waves.com</a></div> 
<!-- end sw-rss-feed code -->
```
