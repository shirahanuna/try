# try
Not everyone writes markdown in the same way, and there are multiple flavors and styles, each of which are valid. While markdownlint's default settings will result in markdown files that reflect the author's preferred markdown authoring preferences, your project may have different guidelines.

It's not markdownlint's intention to dictate any one specific style, and in order to support these differing styles and/or preferences, markdownlint supports what are called 'style files'. A style file is a file describing which rules markdownlint should enable, and also what settings to apply to individual rules. For example, rule MD013 checks for long lines, and by default will report an issue for any line longer than 80 characters. If your project has a different maximum line length limit, or if you don't want to enforce a line limit at all, then this can be configured in a style file.
