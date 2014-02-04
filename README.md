[![vera](https://raw.github.com/wq/wq/master/images/256/vera.png)](http://wq.io/vera)

[Vera](http://wq.io/vera) is the reference implementation of the **ERAV** data model. ERAV is an extension to EAV with support for maintaining multiple versions of an entity with different provenance [^1].

Getting Started
===============

    pip install vera

See [the documentation](http://wq.io/docs/) for more information. See <https://github.com/wq/vera> to report any issues. Note that the vera modules are largely [included within wq.db](https://github.com/wq/wq.db/blob/master/contrib/vera) . The vera package simplifies the installation of additional third-party libraries needed for vera but not required by wq.db.

References
----------

[^1]: Sheppard, S. A., Wiggins, A., and Terveen, L. [Capturing Quality: Retaining Provenance for Curated Volunteer Monitoring Data](http://wq.io/research/provenance). To appear in Proceedings of the 17th ACM Conference on Computer Supported Cooperative Work and Social Computing (CSCW 2014). ACM. February 2014.