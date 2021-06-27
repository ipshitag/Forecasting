# Forecasting
Notes, codes and other materials covered in MDS341A

# Index

1. [Definitions](https://github.com/ipshitag/Forecasting#definition) </li>
2. [What to forecast?](https://github.com/ipshitag/Forecasting#what-to-forecast)
3. [Forecasting data and methods](https://github.com/ipshitag/Forecasting#forecasting-data-and-methods)
4. [Intro to time series](https://github.com/ipshitag/Forecasting#intro-to-time-series)
5. [Steps in Forecasting](https://github.com/ipshitag/Forecasting#steps-in-forecasting)

# Definition

Forecasting is a technique which uses historical data to make informed *predictions* of future trends. Forecasts can be made of different time durations, like,

1. Whether to build a power generation plant in **next 5 years?**
2. Scheduling staff in a call centre for **next week**
3. Stocking an inventory for the **next few months**
4. Investing a capital in requires forecast of **several years**
5. Telecommunication routing requires forecast of **few minutes**

The predictability of an event or a quantity depends on several factors including

- How well we **understand the factor** contributing to it
- How much **data** is available
- Whether the **forecast can affect the thing we are trying to forecast**

One of the important aspects of doing forecast is to see whether the forecast will be good or not. A good forecasting model captures the *genuine patterns and relationships which exist in the historical data,* it also captures the *way in which things are changing*. 

One assumption that is often made, is that, *the environments will continue to change in the same way*, for example, a volatile environment will remain volatile.

Forecasting methods depend on the situation. Forecasting can be done in a very simple way, like *using the most recent observation as the forecast* or can use complex neural networks. One way of forecasting is called *judgmental forecasting,* it is done when there is no data available at all.

**Forecasting** → Predicting the future as accurately as possible, given all the information available, including *historical data* and *knowledge of any future events* that may impact the forecasts.

**Goals** → Goals are the events or prediction that *we want*, it should not confused with plan.

**Planning** → Planning involves determining the *actions* that we would take, *to achieve our goals*.

**Short-term forecasts** → As the term suggests, these are forecasts that are done for short term like scheduling of personnel, production and transportation.

**Medium-term forecasts** → Usually done for forecasting to determine future resource requirements.

**Long-term forecasts** → These kind of forecasts are used for strategic planning

# What to forecast?

As for every project, it is very important to understand what exactly we want to forecast. 

- What are we forecasting?

Apart from this, the knowing the *forecasting horizon* is also necessary. Some questions about forecasting horizons →

- Will the forecast be required for one month, 6 month, a year or ten years?

Another important question is about the frequency in which the forecasts will be used

- How frequently will the forecasts be required?

![image](https://user-images.githubusercontent.com/20279993/123553698-77379980-d79a-11eb-93a7-f1ed28bd80c2.png)

# Forecasting Data and Methods

The method for doing forecasting largely depends on the data available. It can be divided into two main categories

- Qualitative forecasting
- Quantitative forecasting

**Qualitative forecasting** is used when there is no data available or the data available is not relevant.

**Quantitative forecasting** is applied when the following conditions are met

1. Numerical information about past is available
2. It can be assumed that the historic patterns will repeat

## Intro to Time Series:

Time series is a quantitative forecasting method and is very popular, some of the example of time series data include,

- Daily IBM stocks
- Monthly rainfall
- Annual company profits

*Anything observed  over time is a time series*. Time series can be regular intervals and irregular intervals.

The aim while forecasting a time series data is to estimate *how the sequence of observations will continue in future.*

# Steps in Forecasting

1. Problem Definition
2. Gathering Information
3. Preliminary Analysis
4. Choosing and fitting models
5. Using and evaluating a forecasting model

**Problem Definition**

This is one of the most difficult part of forecasting, it focuses on the understanding of

- how the forecast will be used?
- how the forecasting function works within the organization?
- how frequently the forecast will be used?

**Gathering Information**

In all forecasts at least two types of information are required

1. statistical data
2. the accumulated expertise of the people who collect the data and use forecasts

In many cases historical data may not be available, in such cases quantitative modelling is used. Occasionally old data may not be useful because of structural change in system.

**Preliminary Analysis**

All forecasts should start with graphing of data, which can answer many questions, like

1. Are there consistent patterns?
2. Is there a trend?
3. Are there outliers?

and many more...

**Choosing and fitting models**

The tools and models depend on 

- the historical data
- strength of relationships between the forecast variable and explanatory variables
- the way forecast is to be used

Each models is itself *an artificial construct that is based on a set of assumptions*

**Using and evaluating a forecasting model**

Once a model has been selected and the parameters are estimated, the model can be used to make forecasts. The *performance* of the model can be properly evaluated after the data for the forecast period is available.
