---
title: "XPath Contains"
parent: "xpath-constraint-functions"
tags: ["studio pro"]
---

{{% alert type="info" %}}
<img src="attachments/chinese-translation/china.png" style="display: inline-block; margin: 0" /> For the Simplified Chinese translation, click [中文译文](https://cdn.mendix.tencent-cloud.com/documentation/refguide8/xpath-contains.pdf).
{{% /alert %}}

## 1 Overview

The `contains()` function tests whether a string attribute contains a specific string (case-insensitive) as a sub-string.

## 2 Example

This query returns all the customers from which the name contains the string `an`:

```java
//Sales.Customer[contains(Name, 'an')]
```

Customers with the name "Andy" or "Jan" will be returned, for example, because "an" is part of those names.