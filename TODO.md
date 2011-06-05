* -c --config config file to parse(/*.ini format)
* -p --path path to subtitle directory(handle it recursively) or subtitle file
* -l --lang language to look for in the ini section
* parse .ini files(probably with tokens)
    * ignore commented lines
    * use STL vectors(two vectors one for ugly chars and one for replacements)
    * check to have strlen>2 && value before '=' and after '='
    * max line length for reading a line is 256 chars
* .ini section as command line argument for language(no section found => abort)
