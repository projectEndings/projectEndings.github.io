---
layout: page
title: Accomplishments & Outcomes
subtitle: Enabling Sustainable Digital Humanities Projects
---

# Summer 2020

The Endings Project has reached a significant point in its work: It has developed a set of rigorous principles for digital longevity and have also applied
them with complete success to a substantial number of projects. A foundational principle of Endings is that static HTML sites outlast database-driven websites since they contain so many dependencies. One of the biggest challenges our technical support team faced was in creating effective search tools when a database-driven website is converted to a static site. Martin Holmes and Joey Takeda were able to develop search pages that "are better, faster, more configurable and more elegant than what the old databases used to afford developers. The team has already taken down two XML database applications and shut down an entire Tomcat instance. 

## staticSearch Tool Implementation 

Using the Endings staticSearch tool, developed by Martin Holmes and Joey Takeda, The Endings Project has successfully implemented a dynamic to static site generator for XML-based websites. 
As part of the "Endings Toolkit," the staticSearch Tool supports wildcard searches as well as booleans and allows for a variety of search filters. 

⋅⋅* The Map of Early Modern London, edition 6.4.
⋅⋅* The Colonial Despatches, edition 2.1. https://bcgenesis.uvic.ca/search.html
⋅⋅* Mapping Keats's Progress, edition 3.0.

Upcoming: 
⋅⋅* MyNDIR (preview here) https://jenkins.hcmc.uvic.ca/job/MyNDIR/lastSuccessfulBuild/artifact/site/index.html

## Multiple-Editions of Websites

Endings has successfully demonstrated that multiple editions of a website can live side-by-side--just like books on a shelf. This allows long-term projects to publish substantial changes to their websites and produce "newer editions." Users can collate versions of websites in order to see the changes made. Although this functionality might seem beholden to an older logic of "print" production, much of the long-tertm content-creation labour on DH projects is lost when a website is updated without recognition of that labour. By producing "editions" of website, Endings-compliant sites can capture and honour that labour. Moreover, Libraries can accept an edition of these website and serve them without any database requirements. 

### Examples of Multiple Editions 
⋅⋅* The Map of Early Modern London, edition 6.4. MoEML 6.3 <https://mapoflondon.uvic.ca/old/6.3/>

⋅⋅* Despatches 2.0 is here: <https://bcgenesis.uvic.ca/old/2.0/>

# What's Next? 

1. Mariage. This requires that we write stemmers for French in XSLT and JavaScript for the staticSearch engine. That's not trivial but the algorithms are already well-known through the Snowball project, so implementing them is basically no different from implementing the English stemmers we've already written.

2. Early modern English and French pre-processing. Wildcard support in
the search engine is a useful tool when searching digital editions of
texts from the early modern period, because you can work around spelling
variation and obsolete inflectional endings, but it would be even better
if we could pre-process the EM forms into modern forms before
stemming/indexing. Claire and I did a little work on this many years
ago, and I think there are promising approaches we can take that will
make the searches for these sites even better.

3. DVPP (Alison Chapman's project). This site is scheduled for a release
in the fall. It's also entirely static, using the staticSearch engine,
and you can see the development version here:

<https://jenkins.hcmc.uvic.ca/job/DVPP/lastSuccessfulBuild/artifact/products/index.html>

4. Our own Project Endings site. We really need to start eating our own
dogfood, folks.;-)

Anyway, I think we all deserve a drink or two and a pat on the back for
what we've managed to achieve. Well done everyone.

Cheers,
Martin

