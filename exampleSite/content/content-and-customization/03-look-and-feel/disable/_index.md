---
title: Disable features
description: Description depuis le CMS
date: 2021-09-30T00:49:24.052Z
subpage: true
---
You can disable feature in docport by changing some params in `config.toml`

{{< button href="/test" theme="warning" >}}This is a test{{< /button >}}

## Hide Next Page Chevrons

![](chevrons.png?classes=border,shadow)

```toml
	[params]
	disableNavChevron = true
```