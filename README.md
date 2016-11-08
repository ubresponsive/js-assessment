
# Test your JS skills

A set of tests to assess JS skills.

## I want to work on the tests; what do I do?
To use the tests, you will need to install [Node](https://nodejs.org/). Note
that on Windows, there are some reports that you will need to restart
after installing Node - see #12.

You can clone or download this repo. Once you have done so, from the root
directory of the repo, run:

    npm install
    npm start

You can then view the tests in your browser at
[http://localhost:4444](http://localhost:4444).

When you visit that page, all of the tests should be failing; your job is to
get the tests to pass. To do this, you'll need to refer to the tests in the
files in the `tests/app` directory, and edit the files in the `app/` directory.
Once you update a test, you can reload the test page in the browser to see
whether it worked.

You can also run (most of) the tests on the command line:

    npm test

### Available dependencies

The repo includes jQuery, Backbone, and Underscore. You can use these
libraries when writing your solutions!

### Data-driven tests

If your tests need data that can be fetched via XHR, stick a `.json` file in
the `data` directory; you can access it at `/data/<filename>.json`.

## I hate \<some technology you've chosen\>

This repo uses [Mocha](https://github.com/mochajs/mocha) and
[Chai](http://chaijs.com/) for the tests themselves. It uses the BDD style for authoring tests.

