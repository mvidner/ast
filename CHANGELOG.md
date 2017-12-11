Changelog
=========

v2.3.1 (2017-12-xx)
-------------------

* Added AST::Node#to_json.
* Made AST::Node#to_a an alias to speed it up. (#17)

v2.3.0 (2016-06-07)
-------------------

* Replaced String#<< with String#+ to help Opal. (#14)

v2.2.0 (2015-12-19)
-------------------

* AST::Node#clone returns self. (#12)
* AST::Node#inspect outputs Ruby (that assumes you've included AST::Sexp)
* AST::Node#to_s will no longer abbreviate its contents

v2.1.0 (2015-08-03)
-------------------

* Deprecated AST::Processor in favor of AST::Processor::Mixin (#5)

v2.0.0 (2014-04-21)
-------------------

* Added AST::Node#eql? and #hash (#3)

v1.1.0 (2013-06-17)
-------------------

API changes:

  * AST::Processor#process will return nil if passed nil, instead of raising NoMethodError.
