---
layout: post
title:  "JAVASCRIPT PROTYPES!"
author: "Viktor Nikitenko"
date:   2014-09-23 20:46:23
categories: jekyll update
---
<h4> Prototypes are used manily for Inheritance.  
	Every Object in Javascript inherits methods and properties from Object.prototype.  When a message is sent to an Object an attempt is first made to find that property in the Object.If it is not there than it sends the message to the Object's prototype and looks for the property there.  Look at example below.
</h4>
<!-- 
![My helpful screenshot]({{ site.url }}/assets/cheat_sheet_ex1.png) -->
<h4 id="eg_img"> 
	<img src="/assets/cheat_sheet_ex1.png">
</h4>

<h3>You can overide a Prototype</h3>

<h4>One of the things to note from the example above is that Object Car has a protype before we set it to Jeep.  The problem is it's default prototype is empty by default and will not contain the method display.  As a coder we were able to overide the prototpype of Object car to Jeep so it has the method we needed.</h4>
<h3>Using the Prototype Property</h3>
<h4>For an existing proptype, using JS, we are allowed to add new properties or methods at any time.  So lets take the Protype Jeep from the example above.  We want to add a new property that will indicate any Jeep with color black and a function to print_car_detail.</h4>

<h4 id="eg_img"> <img src="..\..\imgs\cheat_sheet_ex2.png"></h4>
<h1>	It's good practice to only modify your own properties and never the ones of standar JS Objects.</h1>
<h3>	Resources</h3>
<h4><a href="http://www.w3schools.com/js/js_object_prototypes.asp">http://www.w3schools.com/js/js_object_prototypes.asp</a>
	<a href="http://sporto.github.io/blog/2013/02/22/a-plain-english-guide-to-javascript-prototypes/">http://sporto.github.io/blog/2013/02/22/a-plain-english-guide-to-javascript-prototypes/</a>
	<a href="http://javascriptissexy.com/javascript-prototype-in-plain-detailed-language/">http://javascriptissexy.com/javascript-prototype-in-plain-detailed-language/</a>
			</h4><!-- 
You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve --watch`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll’s dedicated Help repository][jekyll-help].

[jekyll]:      http://jekyllrb.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help
 -->