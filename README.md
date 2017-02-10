# form-to-struct
Translates an x-www-url-encoded form to a go struct (usable with gorillatoolkit.org/pkg/schema)

`go get github.com/gee-m/form-to-struct`

#### Usage

(Have go's bin path in your `$PATH`)

`form-to-struct --form "your_form=here&with=its-values"`

#### TODO

-[ ] Type detection
-[ ] `-` separated keys