**hi, i’m veit.**

i’m a technologist at large in erlangen, germany.
i work independently at the intersection of **developer experience**, **programming languages**, and **technical due diligence**.
i also have vast experience in **security** and **network automation**, where i spend a lot of my professional engagements.

i live for expressive systems and delightful abstractions. and, occasionally, for magic.

```
(def foldr
  {(f e m) ->
    (({{{} {}} {() -> e}
      {} {() ->
        (({{{} {}} {() -> (f (this m) (next m) e)}
          {} {() -> (f (this (this m)) (next (this m)) (foldr f e (next m)))}}
          (= m {(this m) (next m)})))}}
      (= {} m)))})
```

##### currently

i’m working on security & network automation tools over at [cyberwitchery lab](https://cyberwitchery.com/). find the work [on github](https://github.com/cyberwitchery/), such as [alembic](https://github.com/cyberwitchery/alembic) for a model-centric network
automation tool, [contextual-encoder](https://github.com/cyberwitchery/contextual-encoder) for xss-safe output encoding in rust, or [familiar](https://github.com/cyberwitchery/familiar)
for a simple llm workflow orchestrator.

##### projects & contributions

- [**glamorous toolkit**](https://github.com/feenkcom/gtoolkit): a moldable development environment.
  i contributed to the core, built the first versions of the llm and git tools and worked on various language integrations.
- [**carp**](https://github.com/carp-lang/Carp): a statically typed lisp for realtime applications.
  i work on the compiler and the stdlib, as well as third party libraries.
  you can find more of my work over at [the carpentry](https://github.com/carpentry-org).

##### experiments

- [**metacrap**](https://github.com/cyberwitchery/metacarp): a carp compiler written in carp, including an incremental compiler system for live editor integrations.
- [**mae**](https://github.com/hellerve/mae): maps are everything. an experiment in map calculus.
- [**cspfuck**](https://github.com/hellerve/cspfuck): brainfuck with actors, written in c, without dependencies, with a x86 jit.
- [**cj**](https://github.com/hellerve-pl-experiments/cj): a dependency-free jit framework for c, with backends for x86 and arm64.

##### what i care about

- systems that are moldable, inspectable, and useful
- tooling that respects our time and attention
- speaking & writing about the things we do, because i love teaching & learning

##### elsewhere

[blog](https://blog.veitheller.de), [website](https://veitheller.de), [talks & writing](https://veitheller.de/talks.html)
