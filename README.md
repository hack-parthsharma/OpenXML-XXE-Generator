# OpenXML-XXE-Generator
A small Python script to automate the generation of docx and xlsx XXE payloads.

## Usage
```
usage: generate.py [-h] --host HOST [--protocol PROTOCOL]
                   [--filetype FILETYPE] [--payload PAYLOAD] --outfile OUTFILE
                   [--exfile EXFILE]

OpenXML-XXE-Generator by Richard Clifford & Jordy Zomer

optional arguments:
  -h, --help           show this help message and exit
  --host HOST          The host to use in your payloads
  --protocol PROTOCOL  The protocol to use in your payloads
  --filetype FILETYPE  The type to use in your payloads. Supported formats:
                       svg, odt, ods, pptx, xlsx, xml, docx, odg, odp
  --payload PAYLOAD    The payload to use in your payloads. Supported
                       payloads: rdtd
  --outfile OUTFILE    The resulting payload file. Generated into ./output/
  --exfile EXFILE      The file you want to extract
```

## Contributing?

  Payloads can be added in the payloads.py -> payloads Dictionary.
  
  Filetypes can be added in the filetypes.py -> filetypes Dictionary.
