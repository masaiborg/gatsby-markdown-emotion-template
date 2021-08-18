---
title: "MARKDOWN TEST POST"
category: "Tech"
lang: "ja"
date: "2020-02-02"
slug: "markdown-test"
draft: false
template: "posts"
tags:
  - Gatsby
  - TEST
---

![Gatsby](./gatsby.png)

Please check following:
`contents/posts/2020-02-02-markdown-test/index_ja.md`

## TEXT

HELLO WORLD!

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

## STRONG

**HELLO WORLD!**

**Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.**

## LIST

- 1
  - 1-1
  - 1-2
  - 1-3
    - 1-3-1
    - 1-3-2
    - 1-3-3
- 2
  - 2-1
    - 2-1-1
    - 2-1-2
  - 2-2

## NUMBER LIST

1. No.1
1. No.2
1. No.3
1. No.4

## QUOTE

> HELLO WORLD!

> Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

## DEL

~~HELLO WORLD!~~

~~Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.~~

## CODE

`TypeScript`

```ts
import React, { HTMLAttributes } from "react";
import { style } from "./Style";

export const Card: React.FC<HTMLAttributes<HTMLDivElement>> = ({
  ...props
}) => {
  return (
    <div css={style} {...props}>
      {props.children}
    </div>
  );
};
```

## LINE

---

## TABLE

| header1    |     header2 |   header3    |
| :--------- | ----------: | :----------: |
| align left | align right | align center |
| a          |           b |      c       |
| AAAAA      |       BBBBB |    CCCCC     |
| 00000      |       11111 |    22222     |
| Z          |           X |      Y       |

## LINK

[Gatsby](https://www.gatsbyjs.org)

## CUSTOM TAGS

<test>test tag</test>

<div class="test-div">
<span class="inner">inner Span Tag</span>
TEST-DIV
</div>
