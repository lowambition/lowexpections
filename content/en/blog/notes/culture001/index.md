---
date: 2024-04-24
title: Another land, similar divides
linkTitle: There is no class silly
description: >
  Class, Dutch people often let you know there opinion.
author: Llerrac
resources:
  - src: "**.{png,jpg}"
    title: "Image #:counter"
    params:
      byline: "Photo: Llerrac xela / CC-BY-CA"
---

**This is a part of a series**

I get the feeling I am lightening rod for venting comments on the English.

I have received a lot comments about class. How divided and sitting in the past the Uk is.

One that makes me chuckle.

keyword ['livinginNl']

## Including images

Here's an image (`strawbs.png`) of strawberry plants i hope will bear copious fruit this year.

{{< imgproc sunset Fill "600x300" >}}
Fetch and scale an image in the upcoming Hugo 0.43.
{{< /imgproc >}}

The front matter of this post specifies properties to be assigned to all image resources:



```
resources:
- src: "**.{png,jpg}"
  title: "Image #:counter"
  params:
    byline: "Photo: Riona MacNamara / CC-BY-CA"
```

To include the image in a page, specify its details like this:

```
{{< imgproc sunset Fill "600x300" >}}
Fetch and scale an image in the upcoming Hugo 0.43.
{{< /imgproc >}}
```

The image will be rendered at the size and byline specified in the front matter.


