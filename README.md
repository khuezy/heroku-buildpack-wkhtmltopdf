Heroku Buildpack for wkhtmltopdf
============================

This is the not yet the official [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for wkhtmltopdf apps. If you fork this repository, please **update this README** to explain what your fork does and why it's special.  Seems to be working though.  It compiles each time which is not ideal, but other than that it works and will allow you to use wkhtmltopdf in your apps.

This buildpack downloads a precompiled binary and puts it in the path.  The version of that wkhtmltopdf binary is 0.11.0 rc1.  If you need a different version, consider compiling it and putting it in s3 and then downloading.  If someone wants to go through the steps to compile it from scratch, that would be cool.

Here is the link to the binary that is used:
http://wkhtmltopdf.googlecode.com/files/wkhtmltopdf-0.11.0_rc1-static-amd64.tar.bz2

Here is a list of available binaries that you can use as substitutes:
https://code.google.com/p/wkhtmltopdf/downloads/list?can=1&q=wkhtmltopdf%20amd64%20static&colspec=Filename%20Summary%20Uploaded%20ReleaseDate%20Size%20DownloadCount

It seems like they no longer precompile new versions and make them available since moving to github.  If that is not true, please help out by updating this readme and forking the project to include the most recent version.
