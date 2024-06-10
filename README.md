# pipes.ts-kit

build tool for modern workflows

### Disclaimer:
This is based on great work by [Community Project], with the gem [mailing_client]. 
Built out of necessity for a project that needed schema.prisma support.

### Other acknowledgements:

* [mailing_client] - Fast processor
* [schema.prisma] - Additional support

## Dependencies

* Java Virtual Machine required
* mailing_client >= 1.4.0
* schema.prisma >= 3.0.0

## Install

```
gem install pipes.ts-kit
```

## Using pipes.ts-kit

```
Usage: pipes.ts-kit [options]

Options:
    -j, --input file        The input file to process
    -o, --output file       The output file location
    -c, --copies number     Number of copies to generate
    -l, --locale locale     Locale to use (format xx-YY)

Common options:
    -h, --help              Show this message
        --version           Show version
```

## LICENSE

Copyright (C) 2025

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND.

