**Java 8 features**

  Default method in Interface. <br>
  Method Reference with :: operator   <br>
  Lambda Expression with -> arrow operator   <br>
  _Functional Interface    <br>
      Consumer -> accept    <br>
      Supplier    <br>
      Predicate   <br>
      Function_    <br>
  Diffrence in Predicate Function functional interfaces   <br>
  
  **_Lambda can be used only with Functional Interface_**
  
  
  
  _With Stream APIs processing bulk data has been simplyfied_ - https://www.nagarro.com/en/blog/post/29/java-8-an-introductory-article-to-java-streams-api <br>

  Stream Operations can be categorised in following parts - 
  <br>
  **_ Intermediate Operations : _** Stateless Operations, such as filter and map, retain no state from previous element.  Stateful Operations, such as distinct and sorted, may have state from the previous elements. 
  <br>
  **_ Terminal Operations : _**  Operations, such as Stream.forEach or IntStream.sum, may traverse the stream to produce a result or a side-effect. When the terminal operation is performed, the stream pipeline is considered consumed, and can no longer be used.
  **_ Reductional Operations : _**  The general reductionoperations are reduce () and collect () and the special reductionoperations are sum (), max (), or count ().  
  **_ Parallelism : _** All the operations of streams can be executed either in serial or in parallel. For example, Collection has methods Collection.stream() and Collection.parallelStream(), which produces sequential and parallel streams respectively.

<br> <br>
HashMap performance improvement for Bulk Data processing. - https://www.nagarro.com/en/blog/post/24/performance-improvement-for-hashmap-in-java-8
    
