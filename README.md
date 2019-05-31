# spkg Repository Template
A template for the repository system that spkg uses.

## How it works
spkg uses a repository system similar to apt-get,
where the repo *must* contain a RELEASE file so at least
users know what packages they can install.

## How to use
Firstly, clone/fork this repo to your computer or
Github account. Then, move/upload the packages that
you want to have into the OpenTerm/Libterm folder
(spkg for Libterm is not ready yet.)

It is recommended for you to install a tool from my [repo](https://github.com/sn3ksoftware/sandboxrepo/tree/master)
called `makepkg` to create packages for spkg (OpenTerm).
Install with `spkg -i makepkg`. If you want to make a
package from a script named **foo**, you can run
`makepkg foo`. The package made is foo.tar.gz, which
is compatible with spkg.

If you move/upload a package called “foo” into the
OpenTerm folder, you must add the package name 
(i.e, foo) to the RELEASE file for OpenTerm.

It is strongly recommended for you to also credit the
package author correctly in the placeholder CREDITS
file in either the OpenTerm or Libterm folder.

The formatting of the CREDITS file is as follows:
```
CREDITS
This is a credits file for packages stored in this repo.
The credits are arranged like so:
——————————
Code Author’s Online Alias/Real Name
Names Of Packages
License
——————————
The credits start from here.
——————————
```
Seperate entries for each code author with a line:
`——————————`
# NB
This repo is under the Unlicense.
Enjoy your coding experience!
