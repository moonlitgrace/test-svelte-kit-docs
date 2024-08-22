---
title: Installation
description: Let's see how we can setup icons.
---

# {$frontmatter.title}

{$frontmatter.description}

You can install the package via npm: ( you can use any package manager )
```bash
npm install @coreproject-moe/icons
```

## Usage

You can define package in the main entry file:

```ts
import { defineCustomElements } from "@coreproject-moe/icons/loader";

render(() => {
  onMount(() => {
    defineCustomElements(window);
  });

  return (
    <coreproject-shape-github class="md:size-5 text-accent"></coreproject-shape-github>
  );
}, document.getElementById("root")!);
```
