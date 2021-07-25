# Iterator Questions

a) Do you think making the Graph Iterable makes semantic sense? Discuss briefly, and think of both sides.
An iterable just refers to a collection of objects which can be iterated over. A graph is a collection of vertices that can be traversed through connections, so I think it does make semantic sense. Although since a graph is not linear and there are many ways to iterate over one graph, perhaps it may not make sense to be refered to as iterable.

b) Is a Graph an iterator or an iterable in this case?
The graph is the iterable

c) What would the .iterator method return in this case?

```java
public Iterator<E> iterator() {
    // your code here
}
```

It would return an object of type Iterator, which would have methods such as next() in order to allow the iterable to be iterated over.

d) What is the problem with this approach?
