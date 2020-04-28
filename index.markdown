---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
{% assign tckrepo = "https://github.com/ticktac-project/tchecker" %}

The TickTac project aims to design efficient algorithms and softwares for the analysis of timed automata.

We are developing several open-source softwares:

* [TChecker][tchecker] is a framework for the implementation of verification algorithms for real-time systems. In particular, it proposes a command-line tool that implements a covering reachability algorithm (see the wiki page [using tchecker]({{ tckrepo }}/wiki/Using-TChecker)).
* [tcltl] is an LTL model-checker based on the [TChecker library][tchecker] and [Spot]. [TChecker][tchecker] is used to produce the state-space of the system while [Spot] checks the satisfiability of the LTL formula.
* [uppaal-to-tchecker][utot] can be used to translate [uppaal] models into [TChecker file format]({{ tckrepo }}/wiki/TChecker-file-format).


The project is also proposing a [benchmark][benchmarks] of test-cases.


[tchecker]: {{ tckrepo }} "TChecker"
[benchmarks]: https://github.com/ticktac-project/benchmarks "Benchmarks"
[tcltl]: https://github.com/ticktac-project/tcltl "tcltl"
[Spot]: https://spot.lrde.epita.fr/ "Spot"
[utot]: https://github.com/ticktac-project/uppaal-to-tchecker "utot"
[uppaal]: https://www.uppaal.org/ "uppaal"

