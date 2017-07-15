The Age of Self Reference 
=========================

> May be book

Pop culture anchors of the Age of Self Reference
------------------------------------------------

- The Singularity the will improve itself
- Humanity that faces doom in the hands of its own creation
- Inception: nesting structures common place
- Memes: repetition as the communication architecture
- Matrix: the world embeded in itself. The reality of virtuality.
- Escher: and Douglas Hofstadter of course.

Circularity and Terminality
---------------------------

"It's not the circle's fault if you walk its path endlessly: it's _your_ fault. It's not that the circle describes an infinite path: it's just that you are an _infinite walker_. And quite dumb, by the way. Stop it already." On the Karma Doctrine, Siddartha Gautama (aka Buddha)

> The essence of this argument is that the relationships create the structure and that the root element is in a way the relationship itself.

> The cycle may very well be a non euclidean geometry where the points appear
> in two points in the circle.

Acyclic tree-like hierarchies have, in my mind, a major flaw. The binary tree, for example, is described as starting from a _root_, an initial node, and being successively separated into nodes in amounts that total to powers of two. For every node after the _root_, the node above is the _parent_. That means that there must be a node without a parent. If you think about it, it is a very untidy model, one that does not really make sense beyond intuition. The question is, why? Why should some nodes be special? Is complexity not supposed to be better avoided? How come some nodes have both parent and sons, one "übernode" has no parent and some poorer ones have only parent and no sons? I must confess that is you ask me, it looks awfully similar to a pyramid of social hierarchy and its likely modeled after the same archetype. I was not able to find any other justification for the exceptions. The fact that it remains the go to structure for ordering information makes me think about theory induced blindness, since circular structures are so much tidy and natural to describe the same exact scenarios without the glaring exceptions–that is, without the inconsistency, the complexity and the privilege.

If the binary tree is an infinite one, each node has its own pair of _sons_—otherwise, there are also _leaf_ nodes, final nodes with parent but no sons.

The thing is, where does the _root_ node came from?

Let's try to explain the _root_ node. You can either said about it that it has _no parent_ or that its parent is some axiomatic _supernode_, the _ultimate node_ or something like that. I have philosophical issues with both this approaches, in that it feels that both of them have taken the easy way out of an interesting dilemma regarding the consistency of the graph.

The cycle
---------

Let's start the graph by issuing a single node. This node would be the root node in the usual representation, but that does not work for us since we want a cyclic, no-exceptions-made graph. Instead, the single node is _its own successor_. Ok, let's expand the notion to include a second node. How does this concept scale? Pretty simple, actually: the second node becomes the successor of the first node _and the first node, the successor of the second_.

_Wait a minute!_ you say. _This will become an infinite structure_. Not at all, dumbass. Read the poem starting this article. Circles are not infinite. They are _infinitely walkable_. But you don't need to walk it!

So you want to add a third one. Simple enough: the thirds is the successor of the second and the first is the successor of the third.

At this point, the main difficulty with the argument is linguistical: we simply don't have words for a first element which is also the successor of the last. We are used to think of linear sequences only, and our language reflects that custom.

I have my own set of solutions. Either:

- the _root_ node is its _own parent_, or
- some leaf node is the parent of the _root_ node.

Depending on the case I prefer one or the other. But the main thing is what each of them imply. What they both imply (and, in my guess, the reason they have not been adopted more frequently) is that the "tree" is no longer a tree, but rather a _cyclic graph_.

Cyclic graphs
-------------

A cyclic graph is a more expressive structure than the tree.

### Depth in a cyclic path

The concept of depth in a cylic path is important because it reflect what in a regular path (such as one in a tree) would be considered the _length_ of the path: the depth is defined as the amount of element that you can walk through before a repetition occurs.

Depth reflects the same concepto as _length_. I intend it to be a generalization of length in the context of cyclic paths.

The question: how do you define the length of a cyclic segment in the corresponding non-euclidean geometry?

### Exploiting cyclism: loop chained arrays

In a loop chain—that is, a chain where the last element points to the first one as its parent—it is extremely easy to rearrange the order of the elements when popping one out, since the pointer of the one after it is switched to point to the one before it. Well, that's not _actually that easy_ since it involves walking the entire chain in order to find the element pointing to the current one, but it is straightforward enough. Another neat fact about loop chains is that pushing an element in what would be considered the _top of the stack_ means simply moving the reference that the first element has of the last one to the new element, and pointing the first element towards the new element. Also, the starting point of the chain is kept recorded in the external reference that the related element (the parent, so to speak) has of the first element in the chain. All array operations of pushing, slicing, popping and shifting are somewhat more intuitive in a loop chain array.

This makes a strong case for exploiting the cyclic nature of Pika's linked chains to form loops instead of simple self-references in the first element of the list, as previously proposed. A graphical representation of this feature would be nice to have in order to simplify comprehension.

### Infinity is not just self reference

Self reference _suggests_ infinity but it doesn't _actualize_ infinity. This is formalized in the approach to natural numbers using the _successor_ operator to generate each larger number.

For infinity to be present it would be needed, well, a sort of _material actualization_ of the infinite instances of self reference. In number theory this feature only appears after in some way of the other the existence of an infinity is introduced by a new axiom. Again, the _successor_ function provides the suggestion, opens the door so to speak, to infinity, but does not implies actual infinity as the separate concept of a set of size non describable by any specific natural number.

This is important because there is a common confusion about self referencing structures to beget infinity. Self referencing structures beget replication only because the replication is actualized, but in absence of actualization the self reference is inert. As far as a material operation of the actualization is needed for replication instances to appear, the infinity is not only not implied but even discarded as unreacheable by the simple means of material repetition. In terms of traditional philosophy, infinity is a different substance from matter. In some retorted way, the concept of infinity implies duality and its at the core of the ontological justification of judeochristian theology, since God plays the role of axiomatized infinity which provides a common substance for the spiritual world. I find this approach to metaphysics fascinating and really instructive since the formalization sustains the principle behind the dualism intuitively respalded by religion.

More over, the Freudian concept of _drive_ (at least as related by Zizek) is strongly connected to the _material actualization_ of the self reference in each repetition. Since self replications get expensive under this view, the _drive_ as an active (rather than inert) engine of life becomes a powerful ontological justification of conciousness arising (both inevitably and axiomatically) from a self reference framework.
