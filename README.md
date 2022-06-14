## Introduction to the ggconsort package

[slides]: https://tgerke.github.io/ggconsort-talk/#1
[recording]: forthcoming
[package]: https://tgerke.github.io/ggconsort/

Travis Gerke

This is a 15-minute talk most recently given at [R/Medicine 2021](https://r-medicine.org/).

&#x1F4FA; [View slides][slides]

&#x1F3A5; [Watch recording][recording]

&#x1f4e6; [ggconsort package][package]

&#x270D;&#xFE0F; Abstract: 

CONSORT diagrams are the industry standard graphic for representing participant flow in a clinical trial. Several teams have considered R packages for CONSORT diagram construction, but have fallen short of end-to-end automation. Most notably, Dr. Peter Higgins proposed an excellent CONSORT design overview in his R/Medicine 2020 talk, in which he described the legacy diagram construction as "an artisanal product built by counting categories, then copy and pasting results into templates." Here, I will present a fresh look at the {ggconsort} package, which embraces aspects of CONSORT construction that are inherently artisanal, but eliminates error-prone manual entry. Specifically, I segment CONSORT creation into two stages: (1) CONSORT annotation capture at the time of data wrangling, and (2) diagram layout. I will demonstrate how stage (1) can be built into a single tidyverse chain. Stage (2) maintains some artisanal aspects, but {ggconsort} provides new, helpful geoms to streamline the process.

This talk is for anyone who needs to produce flow diagrams of participant activity in a research study. The workflow is built around the CONSORT diagram standard, but can be also be useful whenever flow charts in R are needed.
