---
title: "Model-based leading indicators for critical transitions"
date: "2012-08-19"
wp_id: 391
wp_type: "post"
original_url: "https://www.vasilisdakos.info/?p=391"
---

In a recent work with Tony Ives, we showed how modified linear models with time-varying parameters can be used to extract an indicator of instability for a time series that may be drifting towards a regime shift. The [paper](http://www.esajournals.org/doi/abs/10.1890/ES11-00347.1) is available online in *Ecosphere.* The idea is simply that instead of fitting an autoregressive model and finding a fixed value for its parameters, to fit an autoregressive model with parameters that change based on the point one is along the time series. This is possible due to a Kalman filter fitting proceedure and seems to not require a too much long time series. We also show that fitting threshold autoregressive models can distinguish alternative attractors in a flickering time series. The code to execute all this is currently in Matlab, but we aim in converting it to an easy to use routine in the R environment.
