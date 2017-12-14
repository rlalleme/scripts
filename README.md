Scripts
=======

Set of scripts for almost anything ... almost.



Installation
------------

Simply copy the repo to some location:

	host:<location_for_scripts>$ git clone https://github.com/rlalleme/scripts.git

Then add the following line to your `~/.*shrc`:

	export PATH=<location_for_scripts>/scripts:${PATH}

It is also advised to clone the documentation as well:

	host:<location_for_scripts>$ git clone https://github.com/rlalleme/scripts.wiki.git scripts/wiki




General consideration
---------------------

All the scripts provide a `-h` or `--help` to print its usage.

All the scripts return `0` when successfull, and any other value if failed (most of the time `99` means wrong parameters, `98` invalid file).



List of scripts
---------------

 - [pdftobooklet](/pdftobooklet): Transforms pdf files into pdf booklet, you then can print the pdf into a booklet by using two-sided, short-edge flipping print option.
 - [template](https://github.com/rlalleme/scripts/wiki/template): Creates a file from a template located in `~/Templates`