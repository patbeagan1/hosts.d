# Blocklists

The tool will scan this folder and its descendants for Yaml and Txt files.

It will gather all of the domain names it can, then alphabetize and deduplicate
them in a "blocklist" section of the generated `hosts` file.

The tests directory is here to show you what is possible - you'll probably want
to replace it with files that better cover your use cases.
