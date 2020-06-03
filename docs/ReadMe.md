# Web Annotation - Test Bench &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

The '[Web Annotation - Test Bench](https://github.com/vpattanaik/WebAnnotation_TestBench)' as the name suggests, is a testbench to evaluate the robustness of the anchoring approaches of textual web annotation tools.

> ## Why?
>A [study](https://link.springer.com/chapter/10.1007/978-3-319-24592-8_2) published in 2015 suggested that of the studied 6281 [Hypothes.is](https://web.hypothes.is/) annotations, 27%  were completely orphaned; and of the annotations that were still attached, 61% were at risk of being orphaned if the live Web page changed.
>
> The [Tippanee](https://chrome.google.com/webstore/detail/tippanee-weave-your-own-w/ccfghgegoegbjgloocplalkhfimgaccb?hl=en) web annotator attempts to solve this issue, by using a novel anchoring algorithm. During initial [experiments](https://doi.org/10.1145/3366030.3366060) the algorithm was found to be more robust to both textual and structural changes.
>
> Now, this testbench is primary designed to compare the robustness of [Hypothes.is](https://web.hypothes.is/)' [fuzzy anchoring](https://web.hypothes.is/blog/fuzzy-anchoring/) approach compared to [Tippanee](https://chrome.google.com/webstore/detail/tippanee-weave-your-own-w/ccfghgegoegbjgloocplalkhfimgaccb?hl=en)'s edit distance-based tree matching approach; and to empirically validate which of the two algorithms is more robust to changes in annotated content.

```sh
In computer science, 'robustness' is the ability of a computer system to cope with errors during execution and cope with erroneous input. [Wikipedia]
```

>:exclamation: *The testbench can be easily modified to evaluate other web annotation tools as well.*


## Samples
The testbench contains a sample of [120 different web pages](/WebPage_URLs.csv) acquired from top 50 [Alexa](https://www.alexa.com/) ranking websites. The websites are divided into 12 [categories](https://www.alexa.com/topsites/category). And, the rankings and web page counts for each of the selected websites are enumerated [here](/Website_Categories.csv).


## Annotations & Variants


## Requirements
* [Visual Studio Code](https://code.visualstudio.com/)
    - VSCode Extension - [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)

## How to Setup
* To host the testbench locally:
    1. Clone the repo.
    2. Open the project folder in VSCode.
    3. Browse to the *http* folder in VSCode *Explorer (Ctrl+Shift+E)* and open *index.html*.
    4. Click on the *Go Live* button on the bottom right corner in the status bar to turn the server on.

> The testbench should open up in the default browser @ *[http://127.0.0.1:5500/http/index.html](http://127.0.0.1:5500/http/index.html)*. Here's what it would look like [:camera:](/docs/imgs/snapshot_frontpage.png).
---

## Licence

This project is licensed under the MIT License - see the [LICENSE.md](/docs/LICENSE.md) file for details.

## Citation
* **TBU**

```
Copyright (c) 2020 Vishwajeet Pattanaik
```
