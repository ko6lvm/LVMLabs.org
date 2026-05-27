---
title: "CodespacesVM"
type: "docs"
tags: ["TAGS"]
draft: false
---

{{< hextra/hero-subtitle >}}
Web-Accessible Linux Virtual Machine.
{{< /hextra/hero-subtitle >}}

<!--more-->

<div class="hx:mt-4"></div>

{{< hextra/hero-badge link="https://github.com/eicv-dev/KSF-On-Codespaces" >}}
{{< icon "github" >}} See on Github
{{< /hextra/hero-badge >}}

{{< hextra/hero-badge link="https://github.com/eicv-dev/KSF-On-Codespaces/blob/main/LICENSE" >}}
{{< icon "scale" >}} GNU GPL
{{< /hextra/hero-badge >}}

{{< hextra/hero-badge link="https://killsecurly.com/tos" >}}
{{< icon "scale" >}} KSF ToS
{{< /hextra/hero-badge >}}

{{< hextra/hero-badge >}}
{{< icon "tag" >}} Software
{{< /hextra/hero-badge >}}

<div class="hx:mt-4"></div>

{{< hextra/hero-button text="See on Github →" link="https://github.com/eicv-dev/KSF-On-Codespaces" >}}

<div class="hx:mt-8"></div>

{{< callout type="info" >}}
  The official CodespacesVM is hosted on `@eicv-dev`'s Github. It is named `KSF-On-Codespaces`.
{{< /callout >}}

<div class="hx:mt-8"></div>

## Setup
### Installation
1. Create a new "Blank" template Github Codespace at https://github.com/codespaces/. However, CodespacesVM is not limited to Github Codespaces.
2. Run the following:
```bash
git clone https://github.com/eicv-dev/KSF-On-Codespaces
cd ~/KSF-On-Codespaces
chmod +x install.sh
./install.sh
```
### Restart
```bash
bash ~/KSF-On-Codespaces/restart.sh
```

## Acknowledgements
* Developed with `eicv-dev`, a contributor and staff member (KSF `DEV2`) of LVMLabs.
* Developed and Maintained under the [KSF Cybersecurity Initative](/software/ksf).
* Initially developed by `Blobby-Boi` but abandoned and later fixed by LVMLabs.