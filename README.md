### togglz
---
https://github.com/togglz/togglz

https://www.togglz.org/

```java
// core/src/main/java/org/togglz/annotation/DefaultActivationStrategy.java

@Retension(RetentionPolicy.RUNTIME)
@Target(ElementType.FIELD)
public @interface DefaultActivationStrategy {
  
  String id();
  
  ActivationParameter[] parameters() default {};
}

```

```
```

```
```


