# Lumen

[Gatsby](https://github.com/gatsbyjs/gatsby) starter for creating a blog.

## Features
+ Clean and extensible code.
+ Lost Grid ([peterramsing/lost](https://github.com/peterramsing/lost)).
+ Beautiful Typography ([matejlatin/Gutenberg](https://github.com/matejlatin/Gutenberg)).

## Installing
Install this starter (assuming Gatsby is installed) by running from your CLI:
`gatsby new lumen https://github.com/wpioneer/gatsby-starter-lumen`

## Running in development
`gatsby develop`

![](http://i.imgur.com/422y5GV.png)

## Tips
If encountering css generation error, try deleting yarn-clean files if that exists. Then reinstall node packages by executing `yarn`. I don't know why, but that works!

### Lets encrypt
First install a tool by `yarn global add gitlab-letsencrypt`.

Run this command every 90 days, replacing the <gitlab token> with your personal token.
```
gitlab-le --token <gitlab token> --email admin@samemoment.com --repository lilac/lilac.gitlab.io --domain blog.samemoment.com
```

## Ports

[Statinamic port](https://github.com/thangngoc89/statinamic-theme-lumen) by [Khoa Nguyen](https://github.com/thangngoc89)

## License
The MIT License (MIT)

Copyright (c) 2016-2017 Alexander Shelepenok

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
