# epidemicmodel
Learning the basics of epidemic modelling via compartmental models in Python
I did this project under the supervision of Prof Raja Paul, IACS Kolkata in December 2021. Then it was mostly data visualisation for COVID-19, and general epidemic modelling. 
Currently, I am extending this project.
Libraries used - matplotlib, scioy, numpy
I will be regularly updating this space with new files, so keep an eye on it!

## Theoretical background
An epidemic, which acts on a short timescale, is a sudden outbreak of a disease
that infects a substantial portion of the population in a region. Often these attacks
recur with long intervals of several years between outbreaks, often diminishing in
severity as populations gradually develop partial or full immunity.
As we are aware, we've just barely exited the throes of a pandemic, unexpectedly
widespread and infectious, and nothing like we have ever witnessed. The virus
behind the pandemic, SARS-CoV 2, showed a range of mutations and in this
situation, it became even more imperative to try to predict what the future course
of the disease would be, so that we can take precautions on a personal and regional
level. One of the most effective ways to do so, is taking existing data and
predicting trends through epidemiological modelling. This has been done quite extensively by epidemiologists and been published in research papers as well as released for public awareness. Such models are useful for a range of epidemics, so there is a level of abstraction to it.<br><br>One pertinent question is that whether epidemiological modelling is still useful,
given that the data based on which the modelling is done is subject to the limits of
experimental error and deliberate inaccuracy, among other things. However,
models are often useful to predict general trends, and keeping a few basic things in
mind, like a basic reproduction number of more than 1 leads to the spreading of
the disease as an epidemic, can give some important qualitative information once
we begin to see patterns in the data.<br><br>There are many questions of interest to public health physicians that could be
answered at least qualitatively with mathematical modelling. For example, how
severe will an epidemic be? What is the maximum number of people needing care
at any particular time, and whether the healthcare system is equipped to handle
that? How long will the epidemic last? How much good would quarantining
victims do in reducing the severity of the epidemic? – these questions can be
answered beforehand (at least to a reasonable approximation) with mathematical
models for epidemiology.
Hence epidemiological modeling is an important part of the knowhow we have
about public health, as well as the means to forming a well-informed set of
decisions about the same in various situations.

## My thoughts
This project was a great learning experience for me. It was interesting to read
through existing literature to find a good model for the pandemic, by looking at
the clinical states of individual persons, and the SIR, SEIR and SEIRD models were simple enough
to understand without being over-simplified. Of course, incorporating time-
varying functions will give much better results for attempts to fit the data to the
model trend. Although this project is by no means an attempt to make predictions in real life, I learnt a lot about how professional epidemiologists advise the government about mitigation measures when a pandemic sets in, before it has fully run its course.

## License
This repository is licensed under the MIT License. Feel free to use the code in this repository for your own learning purposes or projects.
- see the [LICENSE](LICENSE) file for details.

<!-- Authors -->
## Contributors
<a href="https://github.com/mdebasrija/epidemicmodel/graphs/contributors"><img src="https://contrib.rocks/image?repo=mdebasrija/epidemicmodel"></a>
