how to install stuff:
cmd>> py -m pip install [...]

using the data_reader library to pull financial data:
from pandas_datareader import data as wb
wb.DataReader('STOCK', data_source='yahoo', start='year-month-day')