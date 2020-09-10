# Rating ⭐⭐⭐⭐ system

Rating system for wordpress plugin. This library will hlep to plugin developr to add functionality that will ask to user to rate the plugin


## Use

```
        require_once 'rating.php';

        (new \Wpmet\Rating\Rating())
            ->plugin_name('metform')
            ->first_appear_day(7)
            ->rating_url('https://wordpress.org/plugins/metform/')
            ->init();
    
```
