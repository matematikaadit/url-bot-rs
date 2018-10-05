# Known panics

 - Extended network dropouts:

    ```
    thread 'main' panicked at 'called `Result::unwrap()` on an `Err` value: Error(Io(Error { repr: Os { code: 101, message: "Network is unreachable" } })
    ```

 - Poorly formatted toml configuration
 - Various failures connecting to the IRC server, needs added exception handling.

# Possible freeze

 - <kristerman> adds68, remember this? https://open.spotify.com/track/3Z2Thcr0SrxKcQpvouDpR8

# Bad request

    [10:49:29] * benbrown imagines tan wearing https://images-na.ssl-images-amazon.com/images/I/51p9QZZj4lL._UX385_.jpg
    [10:49:29] <wall-e> ⤷ Bad Request

# Cookies

    [14:19:39] <kristerman> https://botw.ticketline.co.uk/order/tickets/13336481/kamaal-williams-at-gorilla-manchester-gorilla-2018-11-06-19-30-00
    [14:19:40] <wall-e> ⤷ Browser cookies are required | Band On The Wall Ticketlin

# Extra features

 - More efficient use of curl (stop fetching page once title has been obtained)
 - MIME matching, image metadata
 - Better handling of IRC connection errors (don't panic)
 - Set config file path on command line option / have default search paths,
   local last
 - XDG paths
 - Batch log processor to add historical logs to the database
 - Investigate [reqwest](https://github.com/seanmonstar/reqwest) as an
   alternative to curl
 - Nick ignore list
 - Lua plugins

# Tests

 - Previous postings
