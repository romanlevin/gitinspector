<h2><img valign="center" src="https://raw.githubusercontent.com/ejwa/gitinspector/master/gitinspector/html/gitinspector_piclet.png" /> About Gitinspector</h2>
<img style="float:right;" src="https://raw.github.com/wiki/ejwa/gitinspector/images/html_example_thumbnail.jpg" />
Gitinspector is a statistical analysis tool for git repositories. The defaut analysis shows general statistics per author, which can be complemented with a timeline analysis that shows the workload and activity of each author. Under normal operation, it filters the results to only show statistics about a number of given extensions and by default only includes source files in the statistical analysis.

This tool was originally written to help fetch repository statistics from student projects in the course Object-oriented Programming Project (TDA367/DIT211) at Chalmers University of Technology and Gothenburg University.

Today, gitinspector is used as a grading aid by universities worldwide.

Please refer to the [[FAQ]] for help on the most common questions.

### Some of the features
  * Shows cumulative work by each author in the history.
  * Filters results by extension (default: java,c,cc,cpp,h,hh,hpp,py,glsl,rb,js,sql).
  * Can display a statistical timeline analysis.
  * Scans for all filetypes (by extension) found in the repository.
  * Multi-threaded; uses multiple instances of git to speed up analysis when possible.
  * Supports HTML, XML and plain text output (console).
  * Can report violations of different code metrics.

### Example outputs
Below are some example outputs for a number of famous open source projects. All the statistics were generated using the *"-HTlr"* flags.

| Project name |||||
|-|-|-|-|-|
| Django | [HTML](http://htmlpreview.github.io/?https://raw.github.com/wiki/ejwa/gitinspector/examples/django_output.html) | [HTML Embedded](http://htmlpreview.github.io/?https://raw.github.com/wiki/ejwa/gitinspector/examples/django_output.emb.html) | [Plain Text](https://raw.github.com/wiki/ejwa/gitinspector/examples/django_output.txt) | [XML](https://raw.github.com/wiki/ejwa/gitinspector/examples/django_output.xml) |
| JQuery | [HTML](http://htmlpreview.github.io/?https://raw.github.com/wiki/ejwa/gitinspector/examples/jquery_output.html) | [HTML Embedded](http://htmlpreview.github.io/?https://raw.github.com/wiki/ejwa/gitinspector/examples/jquery_output.emb.html) | [Plain Text](https://raw.github.com/wiki/ejwa/gitinspector/examples/jquery_output.txt) | [XML](https://raw.github.com/wiki/ejwa/gitinspector/examples/jquery_output.xml) |
| Pango | [HTML](http://htmlpreview.github.io/?https://raw.github.com/wiki/ejwa/gitinspector/examples/pango_output.html) | [HTML Embedded](http://htmlpreview.github.io/?https://raw.github.com/wiki/ejwa/gitinspector/examples/pango_output.emb.html) | [Plain Text](https://raw.github.com/wiki/ejwa/gitinspector/examples/pango_output.txt) | [XML](https://raw.github.com/wiki/ejwa/gitinspector/examples/pango_output.xml) |

### The Team
  * Adam Waldenberg, Lead maintainer and Swedish translation
  * Bill Wang, Chinese translation
  * Christian Kastner, Debian package maintainer
  * Jiwon Kim, Korean translation
  * Kamila Chyla, Polish translation
  * Luca Motta, Italian translation
  * Philipp Nowak, German translation
  * Sergei Lomakov, Russian translation
  * Yannick Moy, French translation

*We need translations for gitinspector!* If you are a gitinspector user, feel willing to help and have good language skills in any unsupported language we urge you to contact us. We also happily accept code patches. Please refer to [[Contributing]] for more information on how to contribute to the project.

### License
gitinspector is licensed under the *GNU GPL v3*. The gitinspector logo is partly based on the git logo; based on the work of Jason Long. The logo is licensed under the *Creative Commons Attribution 3.0 Unported License*.

