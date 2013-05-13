InstantHub Custom Templates
===========================

Right now the hub.igd.fraunhofer.de service uses the pipeline software
provided in this project: https://github.com/x3dom/pipeline. This
repository contains a custom layout template for hub purposes.

There are some special things to consider:

* Only templates that need to be overwritten are stored here. It's not
  a complete set of pipeline templates.
* During development static files are loaded from the pipeline 
  repository right now. A fallback mechnanism as with templates is not 
  possible. For development theres a STATIC_PATH setting you can use, 
  but it's only effective in development and you need to provide all 
  static resources in that directory.
  
