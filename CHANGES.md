Lillebror Changelog
==============

Lillebror follows the Semantic Versioning standard, although not for development
before version 1. Read more at http://semvar.org


Version 0.2.6
-------------

Released on June 28th 2013

- Remove difference calculation on task switches


Version 0.2.5
-------------

Released on June 28th 2013

- Fix bug where a process was sampled after it finished


Version 0.2.4
-------------

Released on June 28th 2013

- Fix error when sampler trying to call not implemented method


Version 0.2.3
-------------

Released on June 28th 2013

- Change the way that context switches are counted (#3)


Version 0.2.2
-------------

Released on June 28th 2013

- Fix bug where CPU couldn't be sampled on Linux (#2)


Version 0.2.1
-------------

Released on June 10th 2013

- Don't specify pyzmq as a setup requirement


Version 0.2.0
-------------

Released on May 10th 2013

- Restructure to modularize samplers and outputs
- Configuration with json/dictionaries
- ZeroRPC output to send samples over network
- PythonSampler to sample with python code


Version 0.1.1
-------------

Released on April 19th 2013

- Add file flushing on write


Version 0.1.0
-------------

Released on February 5nd 2013

- First release
