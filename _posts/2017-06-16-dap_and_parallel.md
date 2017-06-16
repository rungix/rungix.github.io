---
layout: post
title: 'DAP and GNU Parallel'
tags: [gadget]
description: >
    Tools to process the terabyte-sized datasets from censys.
---

The datasets from [Censys](https://censys.io/data) are terabyte-sized, though [DAP: The Data Analysis Pipeline](https://github.com/rapid7/dap) from **Rapid7** can process the datasets, but it isn't fast enough to meet my needs. Lucky to know that [GNU Paralle](https://www.gnu.org/software/parallel/) can speed up the process by splitting the datasets and wrapping the execution across the mulitple cpu cores, so just write a memo when trying to figure it out.
