
# 1.4.3 Other Validation processes

## FAIR
... 
However, as the next figure shows, **three issues** were identified during the evaluation: **p38**. 

*I count 4, not 3 Issues.*
*And I think you misunderstood the F1B recommandation. It is not about the reuse of IRI from other namespace but about the quality of your ontology URI and namespace. `http://www.semanticweb.org/FESMO#` is a dummy URI and namespace, which is perfectly understandable since your ontology is not published. For it to be a real URI, it shoud be accessible : ie ontology should be retrieved by the URI just like `http://www.w3.org/2004/02/skos/core` is ( with the variants https://www.w3.org/2009/08/skos-reference/skos.html for human-readable documentation  or https://www.w3.org/2009/08/skos-reference/skos.rdf for machine readable version). And FAIR checker goes even further, as it recommends to reference your ontology's URI in a registry such as identifier.org (see https://docs.identifiers.org/), to bolster its findability even more*. 
 
*So, I would first dismiss F1B*


F1B "lack of Persistent IDs" : this issue arises because the ontology is not yet published. Thus its namespace and URIs are still temporary (dummy) ones, that do not complying with the recommandation of using a 'globally unique and persistent identifier' ideally backed by a Resolution Service. 

*Then, the 3 other incompletely fulfilled recommandations are partially met for the same reason : the lack of reuse of "ontology classes or properties [...] known in major ontology registries (OLS, BioPortal, LOV). And then again that's easy to dismiss, recalling that your ontology is an ad hoc thing*

3 other recommandations are only partially met : 
- F2B : Shared Vocab for metadata 
- I2 shared Ontologies
- R1.3 Community Standards 

all three due to the lack of reuse of "ontology classes or properties [...] known in major ontology registries (OLS, BioPortal, LOV)" 

The **partial compliance with F2B, I2 and R1.3** is not considered a critical issue in this context. The ontology was
developed ad hoc to address specific needs within its domain, and the decision not to  reuse **other ontologies** was deliberate. This choice ensures that the ontology is tailored precisely to its use case, even though it slightly reduces alignment with external standards. 


## OOPS 

...
These tools help identify potential pitfalls and ensure the completeness and correctness of the ontology by **calculating metrics like class count, property count, and instance count.** *-> seems to me like more complex metrics ? And I don't see the connections with pitfalls ... perhaps you could develop a bit ?*

*You only mention Pitfall30 ... are u sure you don't want to say something about the other ones ? I guess they'r complex and touchy... SOrry, I cannot really help.*

