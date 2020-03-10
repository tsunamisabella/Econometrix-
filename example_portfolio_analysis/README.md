The task is from a pre-assignment for NIB interview, Jan 8th 2020. Unfortunately I was not chosen in the end (I cried for the evening:-( when I received the decision).
However, it is a very good exercise of portfolio analysis.
The task includes data visualization, valuation and forecasting.

data:

(1) data_task_1:

a. Contains a list of financial instruments. Each has a Nominal, a currency and a maturity. 

b. The Nominal shows the amount of a future cash flow and a sign, indicating the direction of the cash flow. 

c. The maturity indicates when the financial contract ends and the Nominal gets paid.


(2) data_task_2 / marketdata:

a. Includes simulated interest rates for a time period of 10 years, e.g. the given value shows the interest rate at that date for all tenors. 

b. The rates at a given moment in time are the same for all maturities


task:

(1) extract and present data

a. Plot the portfolio sorted by currency.

b. Use the given nominals and show the negative, positive cash flows separately 

c. Use the given nominals and show the netted values


(2) analyse fair values over time

a. Calculate the valuations for the instruments for the years 0 to 10 using the given interest rates for USD and EUR.

b. Present the results as they change over these 10 years. 

c. Choose a suitable categorization of the different contributions to the valuation movement.

function:

FV=N*{e^[i*(Tm-Tr)]}^(-1)

FV: fair value of the given instrument

N: the nominal

i: interest rate

Tm: maturity date

Tr: report date as of the fair value is calculated

Note: the fomula is not noted in percent but as an absolute factor 


(3) predict movement for next 3 years (optional)

a. With the given information of the portfolio and the interest rates, introduce a model that predicts the valuation of the portfolio for the next 3 years. 

b. The underlying assumption is that the market remains in its current regime, e.g. that the market continues its movement.	
