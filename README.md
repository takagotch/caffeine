### caffeine
---
https://github.com/ben-manes/caffeine

```java
LoadingCache<Key, Graph> graphs = Caffeine.newBuilder()
  .maximumSize(10_000)
  .expireAfterWrite(5, TimeUnit.MINUTES)
  .refreshAfterWrite(1, TimeUnit.MINUTES)
  .build(key -> createExpensiveGraph(key));

```

```
```

```
```


