Deprecations
````````````
The following modules are deprecated:

- :mod:`matplotlib.compat.subprocess`. This was a python 2 workaround, but all
  the functionality can now be found in the python 3 standard library
  :mod:`subprocess`.

The following classes, methods, functions, and attributes are deprecated:

- ``Annotation.arrow``,
- ``cbook.GetRealpathAndStat``, ``cbook.Locked``,
- ``cbook.is_numlike`` (use ``isinstance(..., numbers.Number)`` instead),
  ``cbook.unicode_safe``
- ``container.Container.set_remove_method``,
- ``dates.DateFormatter.strftime_pre_1900``, ``dates.DateFormatter.strftime``,
- ``font_manager.TempCache``,
- ``mathtext.unichr_safe`` (use ``chr`` instead),
- ``texmanager.dvipng_hack_alpha``,

The following rcParams are deprecated:
- ``pgf.debug`` (the pgf backend relies on logging),
