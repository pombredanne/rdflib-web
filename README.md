
rdflib-web
==========
Two RDFLib web-apps on top of the Flask web-microframework:
 * a SPARQL endpoint app implementing the SPARQL 1.0 Protocol
 * a Linked Open Data app for publishing resources as HTML pages

Each app is available as a commandline-script, or as a Flask Blueprint
for embedding in your own application.

Documentation on ReadTheDocs: http://rdflib-web.readthedocs.org/en/latest/

Installation
------------

Stable version:
```bash
   pip install rdflib-web
```

or most recent:

```bash
   pip install https://github.com/RDFLib/rdflib-web/archive/master.zip
```

Requirements
------------

These are installed automatically if you install with pip

 * For the Web-apps: Flask, http://flask.pocoo.org/
  * (which in turn requires Jinja2 and Werkzeug)
  * For correct content-negotiation: mimeparse (fallback without conneg)
