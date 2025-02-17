# Facts Annotations

Facts are annotated with their confidence level, but more interesting is their <topic>annotation</topic>
with other topics. This section shows how statements can be annotated.

## Regional annotation

Facts can be annotated with the region they are about. We can the list all such <topic>regions</topic>
and the number of facts about that region:

<sparql>regions</sparql>

With gives:

<out>regions</out>

### Putting facts on the map

With the following SPARQL query we can show facts on the world map,
taking advantage of Wikidata [<cite>Q27042516</cite>] to provide geographical coordinates for regions,
using a <topic>federated SPARQL query</topic>:

<sparql>statementOnMap</sparql>

This should show something like this (pending a solution for a `'X-Frame-Options' to 'sameorigin'` problem:

<iframe>statementOnMap</iframe>

For now, this is what the results look like as table:

<out>statementOnMap</out>

## Ecosystems

Similarly, we can list all ecosystems and the number of statements about them:

<sparql>ecosystems</sparql>

Which gives:

<out>ecosystems</out>

## Chemicals

The report also mentions <topic>chemicals</topic> in multiple facts. We have these:

<sparql>chemicals</sparql>

This gives:

<out>chemicals</out>

## Impact

Many facts mention the impact they have. Facts can be annotated with the <topic>impact</topic>.

<sparql>impacts</sparql>

This gives:

<out>impacts</out>

## Drivers

Climate change is caused by both natural and human <topic>drivers</topic>. The report ascribes effects to drivers.
The Wikibase has the following drivers:

<sparql>drivers</sparql>

This gives:

<out>drivers</out>

## References

<references/>
