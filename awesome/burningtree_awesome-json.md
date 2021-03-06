# Information comes from [burningtree/awesome-json](https://github.com/burningtree/awesome-json)
# Awesome JSON [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of awesome JSON libraries and resources.

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list.

* [Awesome JSON](#awesome-json)
  * [Applications](#applications)
  * [Binary Serialization](#binary-serialization)
  * [Browser Extensions](#browser-extensions)
  * [Command-line tools](#command-line-tools)
  * [Databases](#databases)
  * [Datasets](#datasets)
  * [Data modeling](#data-modeling)
  * [Data generation](#data-generation)
  * [Differencing](#differencing)
  * [Format Extensions](#format-extensions)
  * [Frontend components](#frontend-components)
  * [Libraries](#libraries)
  * [Linters](#linters)
  * [Online tools](#online-tools)
  * [Schema Specifications](#schema-specifications)
  * [Services](#services)
  * [Supersets](#supersets)
  * [Related formats](#related-formats)
  * [Resources](#resources)
  * [Templates](#templates)
  * [Testing](#testing)
  * [Text Editor Plugins](#text-editor-plugins)
  * [Transformations](#transformations)
  * [Tutorials](#tutorials)
  * [Queries](#queries)
  * [JSON Schema Frontend components](#json-schema-frontend-components)
  * [JSON Schema Tools](#json-schema-tools)
  * [JSON Schema Resources](#json-schema-resources)
  * [JSON Schema Validators](#json-schema-validators)
  * [Contribute](#contribute)

## Applications
**OS X**
* [Visual JSON](https://itunes.apple.com/app/id488709442) ([github](https://github.com/youknowone/VisualJSON)) - simple JSON pretty-viewer for Mac OS X.
* [JSONExport](https://github.com/Ahmed-Ali/JSONExport) - convert a object to a class of one of the currently supported languages. :star:3300

## Binary Serialization
* [BSON](http://bsonspec.org/) - Binary JSON.
* [MessagePack](https://msgpack.org/) - An extremely efficient object serialization library.
* [UBJSON](http://ubjson.org/) - The universally compatible format specification for binary JSON.
* [CBOR](https://tools.ietf.org/html/rfc7049) - Concise Binary Object Representation.
* [PSON](https://github.com/dcodeIO/PSON) - Protocol JSON, super efficient binary serialization format. :star:318

## Browser Extensions
**Chrome**
* [JSON Formatter](https://chrome.google.com/webstore/detail/json-formatter/bcjindcccaagfpapjjmafapmmgkkhgoa) ([github](https://github.com/callumlocke/json-formatter)) - Makes JSON easy to read. Open source.
* [JSON Viewer](https://chrome.google.com/webstore/detail/json-viewer/gbmdgpbipfallnflgajpaliibnhdgobh) ([github](https://github.com/tulios/json-viewer)) - It is a Chrome extension for printing JSON and JSONP.
* [JSON Browser](https://chrome.google.com/webstore/detail/json-browser/hngfgkmimoikmpohakflgadcajkfnoba) ([github](https://github.com/platy/json-browser/)) - Browse a JSON web with the help of JSON schemas.
* [JSON Finder](https://chrome.google.com/webstore/detail/json-finder/flhdcaebggmmpnnaljiajhihdfconkbj) ([github](https://github.com/rapee/jsonfinder)) - Browse like you do it in Finder.

**Firefox**
* [JSONView](https://addons.mozilla.org/en-US/firefox/addon/jsonview/) ([github](https://github.com/bhollis/jsonview)) - View JSON documents in the browser.
* [JSON-DataView](https://addons.mozilla.org/en-US/firefox/addon/json-dataview/) ([github](https://github.com/warren-bank/moz-json-data-view)) - Displays data in a collapsible tree structure with syntax highlights.

**Safari**
* [JSONAce](https://safari-extensions.apple.com/details/?id=com.acrogenesis.jsonace-56Q494QF3L) ([github](https://github.com/acrogenesis/JSONAce)) - Formats & syntax highlights JSON viewed inside of the web browser using the ACE editor.
* [JSONView](https://safari-extensions.apple.com/details/?id=com.acrogenesis.jsonview-56Q494QF3L) ([github](https://github.com/acrogenesis/jsonview-safari)) - A port of the JSONView Firefox extension that formats and syntax highlights JSON viewed inside of the browser

## Command-line tools
* [jsoncat](https://github.com/pantuza/jsoncat) - Pretty-print Json in terminal with colors and adjusting tabs size. :star:15
* [jq](http://stedolan.github.io/jq/) - A lightweight and flexible command-line JSON processor.
* [json](http://trentm.com/json/) - A "json" command for massaging JSON on your Unix command line.
* [jshon](http://kmkeen.com/jshon/) - A parser designed for maximum convenience within the shell.
* [jarg](http://jdp.github.io/jarg/) - Shorthand JSON and form encoding syntax in the shell.
* [jsawk](https://github.com/micha/jsawk) - Like awk, but for JSON. :star:1242
* [gron](https://github.com/tomnomnom/gron) - Convert a JSON file into discrete assignments that are greppable. :star:4676
* [jid](https://github.com/simeji/jid) - Incremental Digger. Drill down JSON interactively by using filtering queries like jq. :star:4476
* [jiq](https://github.com/fiatjaf/jiq) - It's `jid` with `jq`. You can drill down interactively by using `jq` filtering queries. :star:156
* [jv](https://github.com/maxzender/jv) - jv (for jsonviewer) helps you view your JSON. :star:43

## Databases
* [MongoDB](https://www.mongodb.com/) - an open-source document database, and the leading NoSQL database.
* [RethinkDB](https://rethinkdb.com/) - An open-source distributed document database with a pleasant and powerful query language.
* [EJDB](http://ejdb.org/) - Embedded JSON Database engine. (C)
* [lowdb](https://github.com/typicode/lowdb) - Flat file database built on lodash API. (Javascript)
* [Lawnchair](https://github.com/brianleroux/lawnchair) - A lightweight clientside document store. (Javascript)
* [JSON ODM](https://github.com/konsultaner/jsonOdm) - Object document mapper for JavaScript to use on the server or in the browser. (Javascript)
* [JSON Server](https://github.com/typicode/json-server) - Get a full fake REST API with zero coding in less than 30 seconds. :star:31892
* [Kinto](https://github.com/Kinto/kinto) - A lightweight JSON storage service with synchronisation and sharing abilities. :star:3483
* [CouchDB](http://couchdb.apache.org/) - Seamless multi-master sync, that scales from Big Data to Mobile, with an Intuitive HTTP/JSON API and designed for Reliability.
* [RxDB](https://github.com/pubkey/rxdb) - Event-driven JSON-Database with JSON-Schema, mango-Query and CouchDB-sync. (Javascript)
* [JSONlite](https://github.com/nodesocket/jsonlite) - A simple, self-contained, serverless, zero-configuration, json document store. (Bash)

## Datasets
* [country.io](http://country.io/data/) - Various country related datasets, as JSON inc currency, country codes, names and more
* [countries](https://github.com/mledoze/countries) - World countries. :star:3785
* [vat-rates](http://jsonvat.com/) - VAT rates for all EU countries.
* [MTG JSON](http://mtgjson.com/) - Up to date Magic the Gathering card data.
* [Heartstone JSON](https://hearthstonejson.com/) - Up to date Hearthstone card data.
* [getCountries()](http://peric.github.io/GetCountries/) - Generator for custom Countries data.

## Data modeling
* [JSONModel](https://github.com/jsonmodel/jsonmodel ) - Magical Data Modelling Framework. (Objective-C)

## Data generation
* [jsonymize](https://github.com/cameronhunter/jsonymize) - Reads data from standard input, anonymizes, then writes to standard output. :star:10
* [dyson](https://github.com/webpro/dyson) - Server for dynamic, fake JSON. (node.js)

## Differencing
* [JSONPatch](http://jsonpatch.com/) - A format for describing changes to a document.
* [JSON-Patch](https://github.com/Starcounter-Jack/JSON-Patch) - Lean and mean Javascript implementation of the JSON-Patch standard (RFC 6902). (Javascript)
* [jiff](https://github.com/cujojs/jiff) - JSON Patch and diff based on rfc6902. (Javascript)
* [json-patch-php](https://github.com/mikemccabe/json-patch-php) - implementation of JSON-patch (IETF RFC 6902) (PHP)
* [dffptch](https://github.com/paldepind/dffptch) - A micro library for diffing and patching using a compact diff format. (Javascript)
* [jsondiffpatch](https://github.com/benjamine/jsondiffpatch) - Diff & patch for JavaScript objects. (Javascript)

## Editors
* [JSONEdit](http://mb21.github.io/JSONedit/) - User friendly, visual editor built as an AngularJS directive.

## Format Extensions
* [GeoJSON](http://geojson.org/) - A geospatial data interchange format.
* [JSON-LD](https://json-ld.org/) - A lightweight Linked Data format.
* [JSON-RPC](http://www.jsonrpc.org/) - A stateless, light-weight remote procedure call (RPC) protocol.
* [JSONP](https://en.wikipedia.org/wiki/JSONP) - Safer cross-domain Ajax with JSON-P/JSONP.
* [JsonML](http://www.jsonml.org/) - A compact format for transporting XML-based markup as JSON which allows it to be losslessly converted back to its original form.
* [JSON5](http://json5.org/) - a extension that aims to make it easier for humans to write and maintain by hand.
* [JSON6](https://github.com/d3x0r/json6) - JSON for Humans (ES6). :star:83
* [JSON Resume](https://jsonresume.org/) - The open source initiative to create standard for resumes.
* [JSON Web Tokens](https://jwt.io/) - A compact URL-safe means of representing claims to be transferred between two parties.
* [JSON API](http://jsonapi.org/) - A standard for building APIs.
* [Collection+JSON](http://amundsen.com/media-types/collection/) - A read/write hypermedia-type designed to support management and querying of simple collections.
* [hal-json](http://stateless.co/hal_specification.html) - A set of conventions for expressing hyperlinks in either JSON or XML.
* [JSON Activity Streams](http://activitystrea.ms/) - A format for syndicating social activities around the web.
* [JSON-stat](https://github.com/jsonstat/jsonstat) - Simple lightweight format for data dissemination. :star:14
* [/contribute.json](https://www.contributejson.org/) - Making open source contribution information easier to access, across projects.
* [JSON Table Schema](https://frictionlessdata.io/guides/json-table-schema/) - a simple schema for tabular data
* [NDJSON](http://ndjson.org/) (Newline delimited JSON) - a standard for delimiting JSON in stream protocols.
* [survey.js](http://surveyjs.org/) - JSON based survey library.
* [JSON Meta Application Protocol (JMAP)](http://jmap.io/) - A protocol for synchronising JSON-based data objects efficiently, with support for push and out-of-band binary data upload/download.

## Frontend components
* [JSON editor jQuery plugin](https://github.com/DavidDurman/FlexiJsonEditor) - component for you web apps/pages. (jQuery)
* [jqTree](http://mbraak.github.io/jqTree/) - Widget for displaying a tree structure in html. (jQuery)
* [jsTree](https://www.jstree.com/docs/json/) - jquery plugin, that provides interactive trees. (jQuery)
* [Dynatable.js](https://www.dynatable.com/) - A funner, semantic, HTML5+JSON, interactive table plugin. (jQuery)
* [JSON Formatter](https://github.com/mohsen1/json-formatter) - Angular directive for collapsible JSON in HTML. (AngularJS)
* [react-jsonschema-form](https://mozilla-services.github.io/react-jsonschema-form/) - A React component for building Web forms from JSON Schema. (React)

## Libraries
**C**
* [Jansson](http://www.digip.org/jansson/) - A C library for encoding, decoding and manipulating data.
* [jsmn](https://zserge.com/jsmn.html) - A minimalistic parser in C. It can be easily integrated into the resource-limited projects or embedded systems.

**C++**
* [ArduinoJson](https://github.com/bblanchon/ArduinoJson) - An efficient library for embedded systems. :star:2873
* [JSON++](https://github.com/tunnuz/json) - A self contained Flex/Bison parser for C++11. :star:36
* [json11](https://github.com/dropbox/json11) - A tiny library for C++11. :star:1564
* [RapidJSON](https://github.com/Tencent/rapidjson) - A fast JSON parser/generator for C++ with both SAX/DOM style API :star:6064

**Clojure**
* [data.json](https://github.com/clojure/data.json) - parser/generator to/from Clojure data structures. :star:318

**Fortran**
* [JSON-Fortran](https://github.com/jacobwilliams/json-fortran) - A Fortran library for writing, reading, and manipulating JSON files and data structures. :star:114

**Haskell**
* [aeson-qq](https://github.com/sol/aeson-qq) - JSON quasiquoter for Haskell. :star:49

**Java**
* [JSON-java](https://github.com/stleary/JSON-java) - A reference implementation. :star:2863
* [Fast JSON Processor](https://github.com/alibaba/fastjson) :star:13607
* [Gson](https://github.com/google/gson) - A Java library to convert JSON to Java objects and vice-versa. :star:12602
* [Jackson](https://github.com/FasterXML/jackson) - A multi-purpose Java library for processing JSON data format. :star:3854
* [moshi](https://github.com/square/moshi) - A modern JSON library for Android and Java. :star:3869

**Javascript**
* [JSON-js](https://github.com/douglascrockford/JSON-js) - JSON in JavaScript. :star:7423
* [JSON 3](https://bestiejs.github.io/json3/) - A modern implementation.
* [oboe.js](http://oboejs.com/) - A streaming approach, speeds up web applications by providing parsed objects before the response completes.

**Objective-C**
* [JSONKit](https://github.com/johnezang/JSONKit) - Objective-C library. :star:6188
* [SBJson](https://stig.github.io/json-framework/) - Parse one or more chunks of data.

**Perl**
* [JSON::Tiny](https://github.com/daoswald/JSON-Tiny) - Perl module for encoding and decoding JSON in a minimalistic way. :star:12

**PL/SQL**
* [PL/JSON](https://github.com/pljson/pljson) - A generic JSON object written in PL/SQL. :star:207

**PHP**
* [Webmozart JSON](https://github.com/webmozart/json) - A robust decoder/encoder with support for schema validation. :star:334

**Python**
* [simplejson](https://github.com/simplejson/simplejson) - A simple, fast, extensible encoder/decoder :star:950
* [jsonpickle](http://jsonpickle.github.io/) - Library for serializing any arbitrary object graph.
* [metamagic.json](https://pypi.python.org/pypi/metamagic.json/0.9.6) - An ultra-fast Python 3 implementation of a JSON encoder.

**Ruby**
* [oj](https://github.com/ohler55/oj) - A fast JSON parser and Object marshaller as a Ruby gem. :star:2033
* [MultiJSON](https://github.com/intridea/multi_json) - A generic swappable back-end for JSON handling. :star:618

**React**
* [json2react](https://github.com/txgruppi/json2react) - Use JSON to create React Stateless Components. :star:138

**.NET**
* [jsonfx](https://github.com/jsonfx/jsonfx) - serialization framework for .NET. :star:359

**Scala**
* [spray-json](https://github.com/spray/spray-json) - A lightweight, clean and simple implementation in Scala. :star:740
* [circe](https://github.com/circe/circe) - Yet another JSON library for Scala. :star:1309
* [scala-jsonapi](https://github.com/scala-jsonapi/scala-jsonapi) - Support library for integrating the JSON:API spec with Play, Spray and/or Circe backends. :star:100
* [jsoniter-scala](https://github.com/plokhotnyuk/jsoniter-scala) - Scala macros for compile-time generation of ultra-fast JSON codecs. :star:131

**Swift**
* [SwiftyJSON](https://github.com/SwiftyJSON/SwiftyJSON) - The better way to deal with data in Swift. :star:16936

## Linters
* [jsonlint](https://github.com/zaach/jsonlint) - Parser and validator with a CLI. (Javascript)
* [JSON Lint](https://github.com/Seldaek/jsonlint) - PHP linter. (PHP)

## Online tools
* [JSON Data Ninja](http://www.jsondata.ninja) - The most productive way to visualize and explore tabular JSON data.
* [JSONLint](https://jsonlint.com/) - The JSON Validator.
* [JSONCompare](https://jsoncompare.com/) - The Advanced Version of the JSON Linter.
* [JSONMate](http://jsonmate.com/) - JSON editor, inspector and beautifier.
* [JSON Editor online](http://jsoneditoronline.org/) - A web-based tool to view, edit and format.
* [Collapsible JSON Formatter](http://www.bodurov.com/JsonFormatter/) - Formatter and Colorer of Raw Code.
* [JSON Formatter and Validator](https://jsonformatter.curiousconcept.com/) - Formatter to help with debugging.
* [JSON Generator](https://www.json-generator.com/) - Tool for generating random data.
* [FakeJSON](https://fakejson.com/) - Web API to quickly generate fake data for your application. 
* [JSON to CSV](http://konklone.io/json/) - A free, in-browser JSON to CSV converter.
* [json2csharp](http://json2csharp.com/) - Generate c# classes from a json string or url.
* [JSON Utils](http://jsonutils.com/) - Site for generating C#, VB.Net, and Javascript classes from JSON.
* [geojson.io](http://geojson.io/) - Simply edit GeoJSON map data.
* [jq play](https://jqplay.org/) - A playground for jq.
* [json2yaml](https://www.json2yaml.com/) - Convert JSON to YAML online.
* [JSON Selector Generator](http://jsonselector.com/) - A simple GUI for generating the selectors to access.
* [JSON.fr](https://www.json.fr/) - Fully client-side validator and formatter.
* [ObjGen](http://www.objgen.com/json) - Online live JSON generator.
* [JsonStub](https://jsonstub.com/) - Online JSON faker.
* [JSONPlaceholder](https://jsonplaceholder.typicode.com/) - Fake Online REST API for Testing and Prototyping.

## Schema Specifications
* [JSON Schema](http://json-schema.org/) - a JSON based format for defining the structure of JSON data.
* [Itemscript](http://itemscript.org/ItemscriptSchema.html) - Language for validating and specifying values.
* [Kwalify](http://www.kuwata-lab.com/kwalify/) - A parser, schema validator, and data binding tool
* [Rx](http://rx.codesimply.com/) - Simple, Extensible Schemata.

## Services
* [ipinfo.io](https://ipinfo.io) - JSON IP and GeoIP REST API.
* [JSONProxy](https://github.com/afeld/jsonp) - Simple HTTP proxy that enables cross-domain requests to any JSON API. :star:246
* [Myjson](http://myjson.com/) - A simple store for your web or mobile app.
* [Telize](http://www.telize.com/) - JSON IP and GeoIP REST API.
* [jsonpad](https://jsonpad.io/) - a simple JSON storage platform.
* [JSONP Proxy](https://github.com/fcambus/jsonp-proxy) - A REST API allowing to get JSONP from any API. :star:9

## Supersets
* [YAML](http://yaml.org) - A human friendly data serialization standard for all programming languages.
* [HanSON](https://github.com/timjansen/hanson) - JSON for Humans - with unquoted identifiers, multi-line strings and comments. :star:129
* [μson](https://github.com/burningtree/uson) (uson) - a shorthand for JSON.
* [HOCON](https://github.com/lightbend/config/blob/master/HOCON.md) - Human-Optimized Config Object Notation.
* [ASON](http://www.americanteeth.org/libason/ason_spec.pdf) - A semantically complete superset of JSON (draft).
* [TOML](https://github.com/toml-lang/toml) - A minimal configuration file format that's easy to read due to obvious semantics. :star:7650
* [HCL](https://github.com/hashicorp/hcl) - A structured configuration language that is both human and machine friendly. :star:1437

## Tutorials
* [Introducing JSON](http://json.org/)
* [JSON Tutorial](https://www.w3resource.com/JSON/introduction.php) - An introductory tutorial on JavaScript Object Notation (JSON).
* [JSON - Rosetta Code](http://rosettacode.org/wiki/JSON) - Basic operations in different languages (57 languages in this moment).
* [What is JSON and how to use it](https://ilovecoding.org/lessons/json-what-is-json-and-how-to-use-it) - Video tutorial for beginners.
* [jq Primer: Munging JSON Data](http://andrew.gibiansky.com/) - How jq can be used to process JSON files just as effectively as traditional Unix tools.

## Related formats
* [AXON](https://intellimath.bitbucket.io/axon/) - A simple text based format for interchanging of objects, documents and data. It tries to combine the best of JSON, XML and YAML.
* [CSON](https://github.com/bevry/cson) - CoffeeScript-Object-Notation. JSON for CoffeeScript objects. :star:1119
* [MSON](https://github.com/apiaryio/mson) - Markdown syntax compatible with describing JSON and JSON Schema. :star:681
* [ArchieML](http://archieml.org/) - Structured text format optimized for human writability.

## Resources
* [Type-o-rama](https://github.com/stereobooster/type-o-rama) - JS type systems interportability, comparison of different JS type systems and conversion between them. :star:53

## Templates
* [Jsonnet](http://jsonnet.org/) - A domain specific configuration language that helps you define JSON data.
* [rabl](https://github.com/nesquena/rabl) - General ruby templating with json, bson, xml, plist and msgpack support. (Ruby)
* [json2html](http://json2html.com/) - HTML templating library with wrappers for both jQuery and Node.js. (Javascript)

## Testing
* [JSON Test](http://www.jsontest.com/) - Testing platform for services utilizing JavaScript Object Notation (JSON).
* [JSONassert](https://github.com/skyscreamer/JSONassert) - Write JSON unit tests in less code. Great for testing REST interfaces. (Java)
* [JsonUnit](https://github.com/lukas-krecan/JsonUnit) - A library that simplifies JSON comparison in unit tests. It's strongly inspired by XmlUnit. :star:277

## Text Editor Plugins
**Emacs**
* [JSON Reformat](https://github.com/gongo/json-reformat) - Reformat tool. :star:125

**Vim**
* [vim-json](https://github.com/elzr/vim-json) - A better JSON for Vim: distinct highlighting of keywords vs values, JSON-specific (non-JS) warnings, quote concealing. Pathogen-friendly. :star:944

## Transformations
* [json-sharp](https://github.com/globocom/json-sharp) - Javascript tool to process operations on pure JSON objects. (Javascript)
