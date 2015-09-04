digest-cksum
===========

digest-cksum is a implementation in ruby of the Unix utility cksum 

Usage
-----

```ruby
require 'digest/cksum'

puts Digest::CKSum.file("/path/to/file").checksum!
```
