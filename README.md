# .github
A repository for default Github files for all of sunpy org


These files are copied from the main sunpy/sunpy repo, they should be copied if
they are changed.

## Code of Conduct

The Code of Conduct file apparently needs to be markdown for GH to pick it up,
so the version in this repo is converted from the version in the root of the
main sunpy repo.

The conversion command I used is:

    pandoc -f rst -t markdown_strict ../sunpy/CODE_OF_CONDUCT.rst   > CODE_OF_CONDUCT.md
