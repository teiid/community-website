---
bref: ""
date: 2017-05-16T15:58:18+01:00
description: ""
draft: false
menu:
  sidenav:
    pre: <i class='fa fa-fw fa-rocket'></i>
    weight: -200
  topnav:
    name: quickstart
    identifier: quickstart
    weight: -200
sidebar: sidenav
title: "Quickstart"
toc: true
weight: 20
---

<center>
<iframe width="560" height="315" src="https://www.youtube.com/embed/9vaVMbsHJqk?rel=0" frameborder="0" allowfullscreen></iframe>
</center>

We aim to make it as simple as possible for users to try out Teiid. If you want to try out locally on your laptop, follow the [Using Minishift]({{< relref "#using-minishift" >}}) instructions.

- - -

## Using Minishift

TBD?

### Prerequisites

#### Minishift itself

You're going to need a working Minishift installation, which is really easy. If you haven't got Minishift already installed, please follow the [Minishift installation documentation](https://docs.openshift.org/latest/minishift/getting-started/installing.html).

Fire up Minishift if it's not already running. You need to add some memory, 4192 or more is recommended, and allocate a couple of CPUs:

```bash
$ minishift start --memory 4192 --cpus 2
```

Tip: If you want to switch the OpenShift config permanently use:

```bash
$ minishift config set memory 8384
$ minishift config set cpus 2
```

### Template selection

TBD....

### Deployment instructions

TBD....
