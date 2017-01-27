TheCodingMachine Couscous template
==================================

This package contains a [Couscous template](http://couscous.io/templates.html) used by many [TheCodingMachine](https://www.thecodingmachine.com) open-source projects.
 
Sample project using this template: https://thecodingmachine.github.io/discovery

Note: to use this template, in your `couscous.yml` file, you must add:

```yml
template:
    url: https://github.com/thecodingmachine/tcm-couscous-template.git

scripts:
    after:
        - cd .couscous/generated && npm install && npm run build
```
