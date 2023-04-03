# durable-digitable-artifacts

This note aims to establish a simple ontology for reasoning about durable digital artifacts.

## What is a digital artifact?

Let a digital artifact be a uniquely addressed digital object.

To be a digital artifact the object needs to have interfaces through which it is observed and/or interacted with.

for example,
 - an excel file is a digital artifact 
 - website is a digital artifact
 - a virtual machine is a digital artifact
 - a microservice is a digital artifact


In order for a digital object to be "uniquely addressed" we require that it have a unique, public, universal and idependently verifiable intentifier.

Concretely
- 

Digital artifacts have properties; properties are the specific characteristics relevant to the use of the artifact. As opposed to low level attributes related to the objects fabrication, these are high level attributes that characterize what the artifact does (or does not) do; what the artifact does (or does not) enable someone using it to do. 

In order for a digital object to be "durable" we require that it has a well defined relationship with its future self. That is to say nature of the changes it can undergo without change in its identifier are limit in both scope and frequency.

Specifically, in order for the object to be considered durable, the manner in which it might change must be property preserving. Insofar as properties are able to change over time this should occur in a slow, tranparent and predictable manner. (Think of a large ocean liner changing direction -- thanks to physics it cannot just about-face, this in ability of the ocean liner to change directions rapidy is a property whe can trust assuming we can validate that the ocean liner in question is in fact an ocean liner).

Digital Artifacts may have classes, classes are collections of digital objects which share properties, such that it suffices to infer properties from class membership. In particular, we care about properties related to the manner in which the instances of those artifacts can change over time.

Furthermore, it is possible to technicall verify the following facts
- a class of artifacts share one or more properties (irrespective of the individuation of the artifact instances)
- it is possible to bound the set states that an artifact can reach or the set of actions it can take
- it is possible to define classes which are specifically characterized by the presence or absense of available actions and/or achievable states
- it is possible to prove that a particular digital artifact (one with as specific unique address as previously defined) belongs to class.
- it is possible to create classes which are themselves durable digital objects

an example of a class which is also a durable digible object is a smart contract factory on the ethereum network. A smart contract produced by a smart contract factory on the ethereum network is also a class, it produces further durable digital objects which are transactions.

it is also important to note that the ethereum network itself is a durable digital object. While its state is constantly changing the properties it exhibits are consistent overtime. in the specific instances where it properties changed noticably (excepting the original DAO hack hard fork, at which point the network literally split into two distict identities) all changes to the network were plublic and predictable. Changes such as the introduction of deflationary supply or the switch to proof of stake were "material modifications to the properties of the network" these are moments of substantitive change that required the concerted effort of a large number of people acting in a wide range of capacities -- akin to "terraforming" the physical environment. Due to the level of effort (slowness and transparency of that change), on can argue that ethereum, despite its capacity for change is still durable. 





Some examples of uniquelt addressed digial artifact

## What is a durable digitable object?

