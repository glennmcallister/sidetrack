sidetrack
=========

Trying to make time tracking as simple as possible for software developers.

Most developers consider tracking their time to be a tedious, side task that simply distracts them from doing their real work, namely coding. However, it's often a necessary chore that we all have to deal with. In some cases, it can bring a significant monetary benefit to the company if that time can be shown to apply to government programs, like [SR&ED](http://www.cra-arc.gc.ca/txcrdt/sred-rsde/menu-eng.html).

Many project management systems and bug tracking systems already provide ways of tracking time for a given asset, such as a story, defect, issue, etc.  However, they usualy don't make it that easy to track time spent in meetings, nor to track documentary evidence of the work that has been done, which is usually required by these government programs. 

Sidetrack is an attempt to make a web based system that has a REST API for easy integration with other tools so that developers can either keep track of their time directly inside of the application, or they can synchronize with other systems when necessary.  Sidetrack can act as a bridge between the type of tracking done in [VersionOne](http://www.versionone.com/), [Jira](http://www.atlassian.com/software/jira/overview/), [Bugzilla](http://www.bugzilla.org/), etc., and that required by programs like SR&ED.