# Welcome to spring interview question

####  What Is a Spring Bean?
The Spring Beans are Java Objects that are initialized by the Spring IoC container.
#### Which Is the Best Way of Injecting Beans and Why?
The recommended approach is to use constructor arguments for mandatory dependencies and setters for optional ones. Constructor injection allows injecting values to immutable fields and makes testing easier.
[[1]](https://dzone.com/articles/spring-di-patterns-the-good-the-bad-and-the-ugly)
