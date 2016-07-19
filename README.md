# ScalaReflection
this is a project for learning scala reflection and  scala nsc.

the project will be devided into two parts: the first part will be about scala reflection
the second part will be about scala nsc.


Before start, here, I recommend some official scala documentation about the basic conception about scala reflection:
the URLs are as follows:
1、the overview of the scala reflciton:
    http://docs.scala-lang.org/overviews/reflection/overview.html
2、Symbols, Trees, and Types:
    http://docs.scala-lang.org/overviews/reflection/symbols-trees-types.html
3、Def Macros
    http://docs.scala-lang.org/overviews/macros/overview.html


there are two different Universe:

    1、scala.reflect.runtime.universe: runtime Universe

    2、scala.reflect.marcos.universe : compilation Universe

According to the scala.reflect.api  (http://www.scala-lang.org/api/2.11.0/scala-reflect/#scala.reflect.api.Universe)
there are some Mirrors:
  1、ClassMirror:  A mirror that reflects the instance parts of a runtime class.
  2、FieldMirror:  A mirror that reflects a field.
  3、InstanceMirror:  A mirror that reflects a runtime value.
  4、MethodMirror：   A mirror that reflects a method.
  5、ModuleMirror :   A mirror that reflects a Scala object definition or the static parts of a runtime class.
  6、RuntimeMirror：  he API of a mirror for a reflective universe.
you can see the scala-lang.org for more information about the Class Universe.