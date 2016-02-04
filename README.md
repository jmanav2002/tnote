## tnote

[![GitHub license](https://img.shields.io/pypi/l/pyzipcode-cli.svg)](https://img.shields.io/pypi/l/pyzipcode-cli.svg) [![Supported python versions](https://img.shields.io/pypi/pyversions/Django.svg)]([![PyPI](https://img.shields.io/pypi/pyversions/Django.svg)]()) [![Requirements Status](https://requires.io/github/prodicus/tnote/requirements.svg?branch=master)](https://requires.io/github/prodicus/tnote/requirements/?branch=master) [![Join the chat at https://gitter.im/prodicus/tnote](https://badges.gitter.im/prodicus/tnote.svg)](https://gitter.im/prodicus/tnote?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

```
                            _________ _        _______ _________ _______ 
                            \__   __/( (    /|(  ___  )\__   __/(  ____ \
                               ) (   |  \  ( || (   ) |   ) (   | (    \/
                               | |   |   \ | || |   | |   | |   | (__    
                               | |   | (\ \) || |   | |   | |   |  __)   
                               | |   | | \   || |   | |   | |   | (      
                               | |   | )  \  || (___) |   | |   | (____/\
                               )_(   |/    )_)(_______)   )_(   (_______/
```

A dead simple command line note taking app for you, built while learning [peewee (ORM)](https://github.com/coleifer/peewee)

## Demo

Watch a live demo of it working here

[![asciicast](https://asciinema.org/a/35378.png)](https://asciinema.org/a/35378)

*Here's the [link to previous version](https://asciinema.org/a/35224) if you are interested!*

## Features

- **Dead simple to use**. Even your granny would be able to use it. No seriously!
- **Feature rich** 
  - Add your precious note with it's
    - title 
    - content
    - tags 

  Almost everything you need I guess(**pstt** you ask for feature requests [here](https://github.com/prodicus/tnote/issues))
- **Secure** 
  - Encrypts your database using standard **256 bit AES encryption**. So even if anybody gets hand of your database file. He cannot make any sense of it. 

[Why Advantages of Encryption vs not using it?](https://github.com/prodicus/tnote/wiki/So-you-say-it-is-encrypted-eh%3F)

  **This feature is available/tested only on linux based systems. Support for other OS's coming soon!** 
- **Searching for notes is hassle free** in `tnote`. It supports full text search for notes
  - Search your notes either by it's
    - content
    - tags in it

      Either way, you will always find what you want!

    - The search query if found in the database will be highlighted if found. Looks pleasing to the eyes
- Ability to add and remove tags for each note.
- Adds timestamp for each note which has been added.
- Written in uncomplicated python.

Need I say more?

## Installation

1) `$ git clone https://github.com/prodicus/tnote`

2) `$ cd tnote && pip install -r requirements.txt`

Fire it up! :volcano:

**NOTE** 

On linux system, install `libsqlcipher-dev` 

```sh
$ sudo apt-get install libsqlcipher-dev
```

3) `$ ./tnote.py`

## Contributing

This app was created in a timespan of 2 hours while learning to use peewee. So don't be shy to make some PR's here :smile:

#### To-do
    
- [ ] Add **unit tests**. Like real quick!
- [ ] Make it pip installable
- [x] Add python2 support
- [x] Add tags support for notes
- [x] Add option to add title for notes
- [x] Add option to search for notes using content
- [x] Add option to search for notes using tags
- [ ] Add option to search for notes using title
- [ ] Add option to search for notes using timestamp
- [x] Encrypt the `.db` file using **Sqlcipher**
- [x] Add colorized text to the notes for improved UI
- [ ] Add better UI using **urwid**

#### Contributers

A big shout out to all the contributers, more specifically to these guys

- [@maxwellgerber](https://github.com/maxwellgerber)
- [@BrandtM](https://github.com/BrandtM)

## Motivation

Why not!

## Issues

You can report the bugs at the [issue tracker](https://github.com/prodicus/tnote/issues)

**OR**

You can [tweet me](https://twitter.com/tasdikrahman) if you can't get it to work. In fact, you should tweet me anyway.

## License

Built with ♥ and after a lot of pizzas by [Tasdik Rahman](http://tasdikrahman.me) under [MIT License](http://prodicus.mit-license.org)

You can find a copy of the License at http://prodicus.mit-license.org/
