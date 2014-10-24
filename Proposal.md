

**Introduction**
The discovery and meaningful reuse of research software depends, in part, on accurate metadata. There are many different community standards for describing the contents of a software package, a codebase, or a library package - but these are often substantively different in the attributes that are described, and the details in which they are described - making it difficult to facilitate the discovery of potentially valuable software through APIs or search engines. 

Research in a number of domains also shows that a lack of time, incentive, and training in the creation of metadata hampers progress in sharing, and reusing research objects [e.g. Edwards et al., 2011].

This project proposes the exploration of an emerging science software "minimal metadata" standard in JSON-LD - which offers a simple, core set of attributes to uniformly describe  scientific software in lightweight semantic format. The JSON-LD minimal standard will ease the burden of creating metadata, and also improves the discoverability of software. 

This proposal builds off of the the "code as a research object" project by Mozilla Sciene, Github, and Figshare - and directly contributes to the [ongoing work](https://github.com/mbjones/codemeta) of Matt Jones at NESCENT. 

This project will contribute to the development of this standard through: 

1. A cross walking exercise that maps attribute value pairs from many different existing standards. As the project matures, these categories will converge on a minimum set.

2. Use Cases from ESIP community 

Developing a descriptive metadata standard is a first step in achieving a robust network of software archives. Tools like [Fidgit](https://github.com/openjournals/fidgit) - which are developed to lower the barrier to archiving and obtaining a persistent identifier for code can then be leveraged and used by this network. 


**Some questions and some (preliminary answers):** 





*Why JSON-LD?*

[JSON-LD]() is a lightweight format that offers semantic meaning at a substantially lower barrier of creation than RDF, it has emerged over the last 2-3 years as the standard for serving data via APIs, and more importantly for our work here, it can leverage existing ontologies, like 'creative works' in [schema.org](http://schema.org/Code), for describing a codebase.




### Project Plan, and Timeline


Major work of the use cases will be on the following:   

1. Testing and exploring the use of different subject categories [i.e., we believe we can do better than the original proposal for using [PLoS's taxonomy](http://www.plosone.org/taxonomy) of academic subjects]
 
2. Coming up with guidelines and suggest practices for describing the function of the software. 



### Names and Roles of Team Member

| Name | Role | Description |
|-----------|-----------|------------|
| Nic Weber | Role | PhD candidate in Information Science at University of Illinois. Experience in developing standards and policy for Data Conservancy, and linked data applications. |
| You  | Your Role | Your qualifications |




3. A white paper recommendation [?]

