# Initiatives to encourage R Core contributions

This is a collection of ideas that have been suggested in meetings of the R Core Contribution Team or in discussions with members of the R community about this project. Some ideas are inspired by the work of other developer communities as discussed in this [celebRation2020 talk](https://youtu.be/BbpkKzz71EY?t=1045) and others were taken from the [useR! R Core panel](https://youtu.be/X_eDHNVceCU).

The ideas have been roughly grouped by topic. No importance should be attached to the ordering. Being listed here does not imply any commitment from the R Core Contribution Team to work on these ideas, this is just for insititutional memory. 

## Development Processes

### Support/Documentation

 - 1 page cheatsheet: how to build R
 
 - Dev guide like devguide.python.org
    - include in default docs?/from R-project website?
    
 - Documenting the internal R Core procedures (as part of dev guide?)
     - What are R core working on?
     - Who does what?
    
 - Helper R functions included in e.g. utils, to support common tasks? Or helper scripts included with base R distribution to give quick start to contribution?

### Tech stack

 - Use bugzilla for general issues tracking, not just bugs? (not really sure how this is done right now). Analogous to Python issue tracker. (FYI Python is moving issue tracker to GitHub.)

 - Move to GitLab/GitHub 
    - Continuous integration/continuous delivery that is accessible to non-core for testing.
        - When testing changes, also need to consider the effect on CRAN packages
    
 - roxygen2 for documentation.    

### Opportunities for contribution

Several ideas here based on [useR! R Core panel](https://youtu.be/X_eDHNVceCU).

- Reviewing bugs
- Contributing to R-devel mailing list
    - Requires better moderation to be more welcoming?
- Testing pre-releases
    - write how-to?
    - set up virtual machines for people to test on?
- Help needed on recommended packages too, e.g.MASS, survival 
- Work on how to better credit contributors: within and outside R core.

## R Core structure/support
 
### Structure

 - Imagining the structure of the R Core group of the future (e.g. maybe new appointments are for two or four year terms so that new members don't think they are making a lifetime commitment.)
 
  - Establish roles that are intermediate between outside contributor and R Core e.g. people able to triage issues on issue tracker. Analagous to becoming a Developer on Python issue tracker.

### Finance

 - Developing system to financially support R Core members.
 - Finding the resources to build whatever websites or repos will be necessary to organize documents and deliverables generated by the project.

## Mentoring
 
 - Mentoring on specific projects.
     - see schemes below
 - Mentoring potential R core members 
     * Identifying and publicizing the skill set an R Core candidate must have
     * Identifying candidate R Core members   
 - Establish core-mentorship mailing list (separate from R-devel).
 - Use Zulip for more interactive discussion (and modern format)?
      - potential place for R-core/experienced contributors to offer office hours 
 - R-core/experienced contributors could offer bookable 1-to-1 office hours (e.g. via Zoom)
 - Write a mentoring guide
    - c.f. [R-Ladies mentoring guide](https://tinyurl.com/rladies-mentoring-guidelines)
 - Pair programming of experienced/novice contributors

### Schemes to support mentored projects

- GSoC projects
     - scheme already established, could be used more by R Core
     - or fund some of our own as Julia does: https://julialang.org/jsoc/archive/
 - Similarly Google Season of Docs
     - https://developers.google.com/season-of-docs
 - Establish mentored projects (diversity scholarships)
    - mentees invest 2-5 hours per week over 3 months
    - expenses paid scholarship to useR! conference following year: is there some other incentive we can offer while useR! is online?
 - Outreachy projects
    - paid internship, 40 hours per week over 3 months
    - require mentor(s) to invest 5 hours per week

## Community participation

 - Requests for proposals on perceived deficiencies in R
     - community teams propose solutions
 - Get input from community on ideas via discuss forum like rOpensci?
     - or more formal request for comments	 
 - R-ideas mailing list (analagous to python-ideas mailing list)
 - Analagous process to Python Enhancement Proposal (PEP)?
    - process would be described in the dev guide.
 - Encourage more open developer-focused meetings
    - R core sessions at useR!
    - link to developer-focused meetings e.g. RIOT
    - open attendance e.g. at DSC
 - Developer days: similar to [tidyverse developer days](https://github.com/tidyverse/tidy-dev-day), or [Data umbrella sprints](https://www.dataumbrella.org/open-source/sprints), e.g. [Jun 2020 scikit-learn sprint](https://sites.google.com/view/nyc-2020-scikit-sprint)
     - Curate issues suitable for new contributors
    
## Outreach 

 - Work with Forwards, R-Ladies, etc to reach potential contributors/candidates for any initiatives.
 - R-Ladies attitude: as soon as you know how to do something, teach someone else how to do it (e.g. in Forwards, in R-Ladies group, mentoring/blog post/tutorial).
 - Core devs/bugzilla veterans could offer tutorials
     - will need to be online
    
## Safety

 - Develop/Use code of conduct (with enforcement)
     - for R project as a whole
     - for mailing lists/Zulip
     - for events (N.B. anything held at R Foundation endorsed conference would be covered by that CoC).
    
## Funding

- Funding to support above efforts?
    - R Foundation has potential to support some
    - R Consortium is also willing to support, especially long-term infrastructure
    - other sources to support FOSS projects?

## Openness of this process itself

 - Get input from community on ideas via discuss forum like rOpensci?
 - Post about any initiatives on R blog
    - promote via Forwards, R-Ladies, MiR