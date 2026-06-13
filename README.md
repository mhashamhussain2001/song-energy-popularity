# Song Energy and Popularity Across Genres

An analysis of the relationship between song energy and popularity across six musical genres using 25,736 Spotify tracks.

## Overview

This project investigates whether a song's energy level predicts its popularity, and whether that relationship varies by genre. Using data from the TidyTuesday Spotify dataset, I conducted correlation analysis and fit linear regression models with an energy × genre interaction term.

## Key Findings

* There is a statistically significant but weak negative correlation between energy and popularity (r = –0.08, p < .001)
* Energy alone explains less than 1% of the variance in popularity
* The relationship does not meaningfully vary across genres (Pop, Rap, EDM, R&B, Rock, Latin)

## Methods

* Pearson correlation (overall and stratified by genre)
* Simple linear regression (popularity ~ energy)
* Multiple linear regression with interaction term (popularity ~ energy × genre)

## Tools

R — tidyverse, ggplot2, gtsummary, sjPlot

## Report

📄 **[Download the Full Report](Report.pdf)**

## Data

[TidyTuesday Spotify Songs Dataset](https://github.com/rfordatascience/tidytuesday/blob/master/data/2020/2020-01-21/readme.md)
