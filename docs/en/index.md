# Introduction

## What is this guide?

My collection of best practices



```java title="FooService" linenums="1" hl_lines="2 3"
public class FooService {

    public void doFoo() {
        foo.doSomething();
    }

}
```

``` yaml
theme:
  features:
    - content.code.annotate # (1)
```

1.  :man_raising_hand: I'm a code annotation! I can contain `code`, __formatted
    text__, images, ... basically anything that can be written in Markdown.

    

???+ danger

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.


``` mermaid
sequenceDiagram
  autonumber
  Alice->>John: Hello John, how are you?
  loop Healthcheck
      John->>John: Fight against hypochondria
  end
  Note right of John: Rational thoughts!
  John-->>Alice: Great!
  John->>Bob: How about you?
  Bob-->>John: Jolly good!
```

Using state diagrams

``` mermaid
stateDiagram-v2
  state fork_state <<fork>>
    [*] --> fork_state
    fork_state --> State2
    fork_state --> State3

    state join_state <<join>>
    State2 --> join_state
    State3 --> join_state
    join_state --> State4
    State4 --> [*]
```

## Sample

One more, finally. Or not? :)

Now:

```shell
$ some 
```

Look what she said:

> This is it!

### Subtitle

And now this:

- One
- Two
- Three


#### As well

#### As this

### Another

[a link](https://aws.com)

More?


Can we now have `the build`?

NOW!


Not gonna work, is it?
