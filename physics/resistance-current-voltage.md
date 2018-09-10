# Exploring voltage, current and resistance in series and parallel circuits.
---

### Summary
During this practical exercise, we built two model circuits, each connected to a variable power supply and two lamps in **series** and **parallel** respectively. We then recorded measurements of **_voltage_** across each lamp and **_current_** through the wires for both models. Ideally, one might repeat this procedure several times to account for inaccuracies caused by human error, yet we had limited time in complete the experiment. Once readings were recorded in a table we compared our results to predicted values derived the by **_ohms law_**. If both sets of values correlated to a reasonable degree of accuracy we could say that ohm's law is proven to be true. This is indeed what we observed.

### Ohm's law
Ohm's law, describes the relationship between **_resistance \(R\)_**, **_voltage (V)_** and **_current (I)_**. Put simply, resistance is **proportional** to voltage and **inversely proportional** to current. An increase in voltage will increase resistance, yet an increase in current decrease resistance. Such a relationship can be expressed mathematically using the equation below.
> ![R=V/C](https://latex.codecogs.com/gif.latex?%5Clarge%20R%20%3D%20%5Cfrac%7BV%7D%7BI%7D) 
_R_, Resistance in Ohms (Ω)
_V_, Voltage in Volts (V)
_I_, Current in Amperes or Amps (A)

This holds true for an entire circuit as well as individual circuit components.
Although, the total resistance, voltage or current is not necessarily the sum of said quantities in each component. 

For example, in parallel circuits, the total resistance is actually inversely proportional to the sum of the resistance in each branch. To understand why this is true, we must look at how adding more branches effects current. As it happens, **current will increase as branches are added**, because **more** charge carriers (electrons) travel around the circuit **per unit of time**. As Ohm's law states resistance is inversely proportional to current, this greater current caused by more branches will thus reduce the overall resistance. This relationship can be expressed with using the following equation.
> ![1/R*=1/R1+1/R2...+1/Rn](https://latex.codecogs.com/gif.latex?%5Clarge%20%5Cfrac%7B1%7D%7BR_*%7D%3D%5Cfrac%7B1%7D%7BR_1%7D&plus;%5Cfrac%7B1%7D%7BR_2%7D%5Ccdots&plus;%5Cfrac%7B1%7D%7BR_n%7D)
_R_*, Total resistance in Ohms (Ω)
_R1_, Resistance in first branch in Ohms (Ω)
_R2_, Resistance in second branch in Ohms (Ω)
_Rn_, Resistance in _nth_ branch in Ohms (Ω)

Parallel circuits present other interesting properties such as that the total current split fractionaly between each branch. This occurs because prefer to travel along a path of least resistance. Therefore, where two or more branches are available in parallel, the greatest flow of charge and hence current will be in that of least resistance. If both branches have equal resistance, one half current will be in each; it is split evenly.

In contrast, when connected in series, current remains constant and it is instead voltage which is split. When electrons encounter a circuit component it does **_work_** to move through it, which in turn transfers a **portion** of the electron's **energy** to said component. As voltage (potential difference) is equal to the **work done (energy transferred) per unit of charge**, every time an electron moves through some component, there is a **_potential drop_**. Thus, the potential difference across several components, is simply the sum of each voltage. The fraction of voltage taken by one particular component is dependent on its resistance. By increasing resistance, electrons must do **more work** to move through at a constant rate which results in **greater energy transfer** and **potential drop**.

How does resistance of individual components equate to total resistance in series?
As mentioned, in series circuits, current remains constant. By rearranging _R=V/I_, we can understand how resistance and voltage might change when current is constant.
> ![R=I/V](https://latex.codecogs.com/gif.latex?R%3D%5Cfrac%7BV%7D%7BI%7D)
Multiply by (I) on both sides.
    ![V=IR](https://latex.codecogs.com/gif.latex?V%3DIR)
Divide by \(R\) on both sides.
![I=V/R](https://latex.codecogs.com/gif.latex?I%3D%5Cfrac%7BV%7D%7BR%7D)

If _(I)_ remains constant, then **when voltage increases, so must resistance**. As previously stated, **voltage is proportional to resistance**. Therefore, given that in series, the total potential difference is additive, so is resistance. In other words, **the total resistance is the sum of individual component resistances**.

The table below summaries the properties of resistance, voltage and current, in parallel and series circuits.

| Quantity   | Parallel | Series |
|------------|----------|--------|
| Resistance | Total is **inversely proportional** to the sum of resistance of **each branch**. | Total is **equal to** the sum of resistance of **each component**.
| Voltage    | Remains **constant** for **each branch**. | Total is **equal to** the sum of voltage of **each component**. |
| Current | Total is **equal to** the sum of current in **each branch**. | Remains **constant** for **each component**.

### Experiment data
This practical experiment involved building two circuit models, both with two lamps and a power supply. The first circuit was connected in series and the second in parallel; allowing us to observe differences in resistance, voltage and current between them. Circuit diagrams and our readings are shown below.

```
Circuit model one, parallel.
        +---(V 1)---+
        |           |
  +-----+---|...|---+-----+
  |                       |
(A 1)                     |
  |                       |
  +-----+---(X 1)---+(A 2)+
  |     |           |     |
  |     +---(V 2)---+     |
  |                       |
  +-----+---(X 2)---+(A 3)+
        |           |
        +---(v 3)---+
        
Circuit model two, series.
        +---(V 1)---+
        |           |
  +-----+---|...|---+-----+
  |                       |
  |                     (A 1)
  |                       |
  +-+-(X 2)-+---+-(X 1)-+-+ 
    |       |   |       |
    +-(V 2)-+   +-(V 1)-+
```

| Measurement           | Parallel | Series |
|-----------------------|----------|--------|
| V1, EMF (V)           | 7.50     | 7.50   |
| V2, First lamp (V)    | 7.73     | 3.52   |
| V3, Second lamp (V)   | 7.72     | 3.76   |
| A1, Main wire (A)     | 0.15     | 0.12   |
| A2, First branch (A)  | 0.07     | n/a    |
| A3, Second branch (A) | 0.07     | n/a    |

From this data we can see that the voltage of each individual lamp within the series circuit is roughly half of the total EMF (1/2 of 7.50 = 3.75) = V2, V3 ± 0.3. Yet, this is not perfect; summing V2 and V3 gives a value less than the EMF. One could simply attribute this to machine error, yet this is more likely due to internal resistance of wires. That is, total circuit resistance is contributed to by the resistivity of the wires. Thus, as voltage is proportional to resistance, the EMF is increased. To which degree this effect is noticeable is dependent on wire material, length and cross sectional area. Overall, this appears to prove Ohm's law for voltage in series as discussed above; voltage is split between each component.
Regarding the set of parallel readings, they also appear to confirm other presumptions. Both V2, and V3 share a similar voltage to the EMF with relatively small error, thus showing each component receives equal voltage in parallel. Although A2 and A3 have identical current readings, this does not dispute the notion that current is split in parallel, no. Given that both branches have equivalent resistance caused by matching lamps, one should expect an equal current within both. This is exactly what we observed and therefore proves the hypothesis.

In conclusion this experiment was successful as we recorded enough readings with minimal error, to draw conclusions about the relationship between resistance, current and voltage in parallel and series circuits.


