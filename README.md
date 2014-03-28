chrome-extension-boilerplate
============================

A minimalistic boilerplate to speed up your Chrome extension development

Installation
------------

The easiest way to install this boilerplate is to run

        $ git clone --depth 1 https://github.com/mrshu/chrome-extension-boilerplate.git

That will, however, create a directory called chrome-extension-boilerplate
which might not be what you want. Thus you can run the following command to
clone this repository into current directory

        $ git clone --depth 1 https://github.com/mrshu/chrome-extension-boilerplate.git .

Sometimes, you might want to add this boilerplate to a folder that already
serves as a git repository. In that case the following oneliner might come
handy

        $ cd /tmp/ && git clone --depth 1 https://github.com/mrshu/chrome-extension-boilerplate.git && cd chrome-extension-boilerplate/ && rm -rf .git/ README.md LICENSE

After executing it there should be a directory in /tmp that contains the bare
boilerplate.
