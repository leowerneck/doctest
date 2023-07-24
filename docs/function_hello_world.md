---
layout: default
title: hello_world()
nav_order: 2
---

{: .function }
> ```c
> void hello_world(char *string1, char *string2);
> ```
>
> This function prints the message `<string1> Hello, world! <string2>` to the screen. A new line character (`\n`) is added to the end of the string printed.

{: .warning }
Testing the warning callout.

## Test 1

```c
void hello_world(char *string1, char *string2);
```

## Test 2

{: .function }
> ```c
> void hello_world(char *string1, char *string2);
> ```

## Test 3

<div class="language-c highlighter-rouge">
    <div class="highlight" style="background-color: $blue-000">
        <pre class="highlight">
            <code>
                <span class="kt">void</span>
                <span class="nf">hello_world</span>
                <span class="p">(</span>
                <span class="kt">char</span>
                <span class="o">*</span>
                <span class="n">string1</span>
                <span class="p">,</span>
                <span class="kt">char</span>
                <span class="o">*</span>
                <span class="n">string2</span>
                <span class="p">);</span>
            </code>
        </pre>
    </div>
<button type="button" aria-label="Copy code to clipboard"><svg viewBox="0 0 24 24" class="copy-icon"><use xlink:href="#svg-copy"></use></svg></button></div>


Function arguments:

<dl>
  <dt>string1</dt> <dd>String printed before message <pre>Hello, world!</pre></dd>
  <dt>string2</dt> <dd>String printed after message <pre>Hello, world!</pre></dd>
</dl>
