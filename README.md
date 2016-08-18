#Memcached Reduxe for WordPress

Доработанный форк memcached-redux

# Описание

Changes the famous Memcached WP Object Cache backend to actually use the Memcached class (not the Memcache class). Implements wp_cache_get_multi() and wp_cache_set_multi()

```php
<?php
wp_cache_get_multi( array(
    array( 'key', 'group' ),
    array( 'key', '' ),
    array( 'key', 'group' ),
    'key'
) );

wp_cache_set_multi( array(
    array( 'key', 'data', 'group' ),
    array( 'key', 'data' )
) );
```

Blog Post: [http://scotty-t.com/2012/06/05/memcached-redux/](http://scotty-t.com/2012/06/05/memcached-redux/)