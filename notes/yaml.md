yaml stands for yent another markup
language meaning yaml is not a markup
language like html and xml
a markup language is a system for
annotating a document in a way that is
visually distinguishable from the
content
html is the best example of markup
language
* well if it is not markup language what
it is
it is a ***serialization language***
i am sure that you know what
serialization is

* let's understand what serialization is
in simple terms
when you want to send some data from one
system to another system you need to
send it over a network as a byte stream
so you convert your data to binary and
send it over a network and the receiving
system will convert the binary back to
the original data
but when you want to send an object the
receiving system may not reconstruct the
exact object from the binary it received
because of different os or the languages
used.
* so the data must be sent in a format
that can be understood by both machines
so instead of converting your objects
directly into binary we convert the
objects to a commonly agreed format that
can be understood by both systems
those common formats are called
***serialization languages***
and the process of converting from
objects to binary is called
## ***serialization*** and the reverse process
##
which is converting the binary back to
the original data is called
***deserialization***
examples of serialization languages are
yaml
json and xml
yaml is more data oriented than markup
oriented it's recommended that
configuration files be written in yaml
rather than json this is because
yml has better readability and is more
user friendly the main benefit of
writing spec files in the yaml or json
files is
those files can be added to the source
controls such as github so that the
changes can be tracked and audited
this is the simple yaml file the same
content can be written in json or xml
with different syntax
json uses curly braces and xml uses
angle brackets and yaml doesn't use any
such special characters
instead it uses line separation and
indentation
this makes the yaml cleaner as you can
see let us try to create a simple aml
file and see what all we can write in
the ml file
i'm on the vs code and i'm creating a
new file
clusters.yaml
the extension can be yaml or just yml
let's go with yaml
in general most of the things in yaml
file are in the form of key value pairs
like
name
local
cluster
so here we are specifying the cluster
name as local cluster so the general
syntax would be key colon
space and the value space after the
colon is mandatory the other example
would be
is active as
true
so this is the boolean value we are
giving
ml supports different data types like
boolean string integer etc you might be
wondering why this string is not
enclosed in double quotes
you can use double quotes or single
quotes are no goods that doesn't make
any difference
we can write these ml files in any text
editor like notepad or ides
most of the ids have an extension for
yaml to validate its syntax
as we are on vs code we can find out the
extension for the ml and install it as
you can see this is the extension by red
hat it's already installed in my vs code
if it's not installed go ahead and
install it now our vs code can validate
the syntax
as yaml is indentation based there are
lot of chances for syntax errors so an
extension like this will be of great
help now let us try to delete the space
after the colon and see what happens as
you can see the red indication here it's
saying it's invalid that way the ids
will be of great help to validate the
syntax on the fly there is nothing
specific to the naming convention that
we use in yaml some people uses camel
case and some people uses snake kiss as
k8s uses camel case let's go ahead with
camel case we can also give dates like
created it
