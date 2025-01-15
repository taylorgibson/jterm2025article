---
title: My Cool Title
abstract: |
  This paper will blow your mind.

  Really, you will love it!
---

## Introduction
This this an introduction (https://doi.org/10.1038/s41586-024-08275-2)

## Methods
Here are my methods [@10.1038/s41586-024-08275-2]

Here's the book I used @paar_understanding_2024

@erickson_data_2019

| column 1 | column 2 | column 3 |
| -------- | -------- | -------  |
| data 1  | data 2   | data 3   |
| data 4   | data 5   | data 6   |



```{list-table} Mr. Gibson's Table
:header-rows: 1
:label: gibson-table

* - column 1
  - column 2
* - data 1
  - data 2
* - data 3
  - data 4
```

The data contained in @gibson-table is really important to this paper.

```{csv-table} Frozen Delights!
:header: "column 1", "column 2", "column 3"
:label: csv-example-table

"Albatross", 2.99, "On a stick!"
"Crunchy Frog", 1.49, "If we took the bones out
it wouldn't be crunchy, now would it?"
"Gannet Ripple", 1.99, "On a stick!"
```

The data in @csv-example-table is pretty cool

```{figure} images/sunset.png
:label: beach-vacation
:alt: A serene sunset view at a beach, featuring a vibrant orange sky reflecting on calm ocean waters. The foreground includes several thatched parasols and lounge chairs arranged on a pebble beach, creating a relaxing and tranquil atmosphere.

Sunset at the beach
```
This past year I took a vacation to a nice beach. See @beach-vacation for an image of my view at the beach.


```{figure}
:label: subfigure-example
:align: left

![Here is a sunset](images/sunset.png)

![Here are some graphs](images/grapes.png)

Look at my cool photos
```

Here's a reference to @subfigure-example-a and @subfigure-example-b. The group of subfigures is @subfigure-example


![Fish table example](#fish-table)

```{figure} #fish-histogram

Cool histogram of some fish data
```
```{figure} #fish-plot
:label: fish-plot2 

Here's a line graph
```
```{mermaid}
flowchart LR
  A[Jupyter Notebook] --> C
  B[MyST Markdown] --> C
  C(mystmd) --> D{AST}
  D <--> E[LaTeX]
  E --> F[Gibson]
  D --> G[Word]
  D --> H[React]
  D --> I[HTML]
  D <--> J[JATS]
```

## Results
Wow, great results.

## Discussion
Can you believe how good I am at this science stuff?

## Conclusion
Mr. Gibson for head of the NSF