#How to setup JSON Server

###Clone this repository
{% highlight %}
git clone git@github.com:gurindernarang/json-server.git
{% endhighlight %}
###Install JSON Server globally on your system
{% highlight %}
npm install -g json-server
{% endhighlight %}
After sucessfull installation of json-server and cloning this repository, move into this repository and run json-server on your system using following command
{% highlight %}
json-server --port 3001 --watch db.json
{% endhighlight %}