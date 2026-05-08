# Abstraction 

## Definition:
```
Abstraction is the cognitive and intellectual process of extracting the essential, defining qualities/structure of something while deliberately omitting or suppressing the non-essential, context-specific, or irrelevant details — resulting in a simplified, generalized representation that captures the idea of a thing rather than any particular instance of it.
```
Analogy: Magnification of skin
Algorithm:see obejctive.md
1/Exact the whole structure details 
2/ Remove the detials/Structures based on goal
3/ Now there are two possible ways to remove
 3.1/ Since we can use the advantage of abstraction characteristic that it should be generic,and it leads to specifc cases.so we can simply remove the sepcifc cases of the strcuture.but this mostly leads to non-uniform abstraction
 3.2/ Comparable Abstraction
 3.3/Non-comparable abstraction
4/ Now the result is called schema where it does have lost the infromation due to removing case-specfic structures.


## NOTE
```
-   If u fail to abstract then either of the following has to be true

    1/ U did mistake while extracting the structure ,persepctive and context of the system or the extracted structure,percpective  and context is icomplete

    2/ U didn't use a correction removal method
- During instantiation the core strcuture is maintain,what i mean by core strcuture ,core strcuture means that specifically start from 1 st layer and end at n th layer,and it is contineous like layer1->later2....layern,!no discontinuity,if there is any discontunity then it is called decompositon not abstraction
```

## Operations
```
At its core, abstraction involves two simultaneous operations:

    Generalization — identifying what is common or essential across multiple specific instances.
    Suppression    — consciously ignoring the particulars that differ between instances or are irrelevant to the purpose at hand.

The result is a schema,model or representation that is less concrete than the original but more broadly applicable.
```

## Key Characteristics(Question based!!)

### Q1> How do we know what has to removed and how much has to be removed
```
> Purpose/Goal/Perspective/Context-relative — what counts as "essential" depends on the goal. The abstraction of "a chair" for a furniture designer differs from that of an ergonomics researcher.


> Uniform vs Non-uniform abstraction
![Uniform vs Non-Uniform abstraction Diagram](C:\Users\negfl\Desktop\uniform_non_uniform_abstraction.png)

-Description of Diagram:The Diagram is essentially an analogy for abstraction,where  the inner layer represent core structure upon which outer layer(Periphery structure) is built on.Lines represent the boundaries of parts of the structure.

- Since one of the operation of abstraction is removal of strcutures,in that there are two type uniform and non-uniform removal
- Uniform:In uniform removal we remove the part's strcuture such that every part has same level of abstraction,that is we remove the outer layer and leave the inner layer untouched.
- Non-uniform removal :In Non-Uniform removal we remove the part's structure such that it has non-uniform abstraction,that is we remove the outer layer completely and remove a part of inner layers.So that each part will have uneven levels of abstraction.
- Rule:you can't remove the inner layer and keep the outer later(well there is a no other type of abstraction where  breaks this rule)

> Comparable vs Non-Comparable Abstraction
Comparable Abstraction:In Comparable abstraction we  have  other structure to compare,so based on  the other structure we try to remove the details and find the generic strcuture
Ex: Analogy transfer
Scenario: You know the solution of Problem A but don't know the solution of problem B,so you try to see if they problem A and B has any generic structure,so in this case the comparable structure is problem B,so what you essential do is you try to extract the schema of A and B,and compare it ,and we try to see if there is some similarity between schema A and B,if there is then we tranfer the solution.
Non-Comparable Abstraction:In Non-comparable abstraction  we dont have any comparable objects.so in that case we try to divide the structure into its part  and abstract each part by comparing with other parts such that they land up in same level of abstraction(Uniform-abstraction but with process).You can take this a method for Analogy transfer Strategy.
Ex:Sink and water analogy


```
### Q2> What is the impact of perspective in abstraction
```
> Impact of perception:Two perspectives on same system can sometimes produce completely abstraction map,well that depends on what you focus while abstracting
Ex(Analogy):
Let's human skin
ok,A Biologiest who's focus is finding the fundamental building block of humans,so he took the skin and maginified it ,now during maginification the information is lost(How:if u take maginifying lens ,which is round in shape,that acts as boundary because while he is seeing through lens he will not look at outside the boundary),now if u ask him he will say cell is fundamental building block,so his map will be cell->skin(this is also wrong explanation),actual u have to take structure information cells->cell_groups->skin,now abstract it,now we know in abstraction specfic cases will increase,by remove the skin and cell_group,we get cell which is more abstract which give possiblity to many type sof cell_groups and skin,at the same time removin skin and cell_group we lose information.

ok,now lets take a physict who's focus is interaction and assume he has very powerful eyes,so he took the skin and looked at a part of it (wrong why,because we dont abstract in the why the physics do,we take the all the information and create schema ,
by definition we schema has low information)

What you can learn: While abstracting somthing ,we first take the who structure  and abstract it by removing specific case information,so we get to schema

```
> Layered — abstraction exists on a spectrum. A dog is an abstraction of a specific animal; mammal is a higher abstraction; living organism is higher still.see Layer diagram to get a better analogy

> Lossy by design — information is intentionally discarded. This is a feature, not a flaw — the loss of detail enables broader reasoning.see Bacteria analogy


> Reusable — because an abstraction is detached from specific instances, it can be applied across many different concrete situations.

> Directionality — abstraction moves away from the concrete toward the conceptual; its inverse is instantiation or concretization (moving from concept back to a specific example).
