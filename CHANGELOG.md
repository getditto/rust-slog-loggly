## v0.3.2 (2019-06-20)

* Fix the timestamp format

## v0.3.1 (2019-06-20)

* Send event timestamp to Loggly to avoid event reordering
* Switch to Rust 2018

## v0.3.0 (2018-08-29)

* Switch to Hyper 0.12.x and the new tokio

## v0.2.3 (2018-05-22)

* Fix an issue with disappearing messages

## v0.2.2 (2018-05-16)

* Disable keep alive (Hyper client)
* Disable request retry (Hyper client)

## v0.2.1 (2018-05-10)

* Make the Error struct public
* Implement Clone for the FlushHandle

## v0.2.0 (2018-05-09)

* Fix duplicate keys in the JSON message
* Add API for flushing the drain

## v0.1.1 (2018-05-02)

* Add debug mode

## v0.1.0 (2018-04-18)

* Initial release
