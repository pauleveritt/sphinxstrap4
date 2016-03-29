Changes
=======

Here are some places where sphinxstrap4 deviates from alabaster. As a general
principal, sphinxstrap4 tries to get out of configuration-driven styling,
into less-noisy templates.

- Removed configurable doctype block and instead just uses html doctype

- Fork the sphinx basic/layout.html template and replace it with markup from
  sphinxjp.themes.basicstrap

- Force that to be dependent on BS3, fixed navbar, and fluid

