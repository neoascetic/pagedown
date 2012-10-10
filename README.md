This is a clone of [pagedown][], [markdown][] editor used on [SO][] with live
preview, one from lot of others. This fork adds support for emails autolinking
and custom selectors:

    var editor = new Markdown.Editor(
        converter,
        {
            buttonBar: '#buttonBar',
            preview: '#preview',
            input: '#input'
        }
    );



[pagedown]: http://pagedown.googlecode.com/
[markdown]: http://en.wikipedia.org/wiki/Markdown
[SO]: http://stackoverflow.com
