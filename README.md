## Link analysis of IMDB movie connections

Code for the blog post: [Link analysis of IMDB movie connections][]

## Usage

    $ git clone git://github.com/jberkel/imdb-movie-links.git
    $ cd imdb-movie-links
    $ easy_install networkx imdbpy
    $ brew install graphviz wget   # OSX/homebrew
    $ bundle install
    $ rake rank                    # CSV export ranking
    $ rake graph.svg MAX=50        # create a graph, max. 50 nodes

## Credits

 * [NetworkX][] python library, Copyright (C) 2004-2010, NetworkX
 * [IMDbPY][]

## License

Released under the term of the GNU GPL license, see LICENSE.

[Link analysis of IMDB movie connections]: http://zegoggl.es/2010/12/link-analysis-of-imdb-movie-connections
[NetworkX]: http://networkx.lanl.gov/
[IMDbPY]: http://imdbpy.sourceforge.net/
