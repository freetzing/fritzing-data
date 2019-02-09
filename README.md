# fritzing data

This repository is a collection of Fritzing data files pooled together for testing of the [fritzing-js](https://github.com/freetzing/fritzing-js) library.

## Why is this needed?

When the authors of `fritzing-js` were building the early versions of the library, they discovered several components of Fritzing data that were not covered in the Fritzing documentation. To ensure that the `fritzing-js` library can effectively retain all of the data from these files, this repository was put together so that we could support user-generated Fritzing data files instead of just the default files that come with the Fritzing app. If you cannot find your own content here, feel free to **submit a Pull Request**.

## Usage

When the `fritzing-js` library is tested, this repository is cloned in a local directory and then used to test each module of the library against its corresponding Fritzing data files.

|Fritzing data | Library module                         |
|---------------|--------------------------------------|
|FZP            |Part            |
|FZ             |Sketch      |
|FZB            |Part Bin   |
|FZZ            |Sketch Bundle  |
|FZPZ           |Part Bundle    |
|FZBZ           |Part Bin Bundle             |


## Contributing

**Pull Requests are welcome!** Help contribute to this repository by adding Fritzing data that you find out in the wild. The more data that we can test against, the more complete `fritzing-js` gets.

## License

Any and all Fritzing data found on this repository *is the property of others*. These files were created and published under the [Creative Commons Attribution-ShareALike 3.0 Unported](http://creativecommons.org/licenses/by-sa/3.0/) with the help of the Fritzing organization.