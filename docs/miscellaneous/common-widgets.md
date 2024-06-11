# Common Widgets

## Period Picker

![Period Picker](../images/period-picker.png)

The period picker adjusts the chart relative to **the date of the latest data point**.

**How `3M/6M/1Y/3Y` options work**:

Selecting these options will always display a chart starting from the start of a month. For example, if the latest data point is dated 2020-06-15, selecting `3M` will truncate the data starting from 2020-03-01 - the current month is always considered in its entirety.
