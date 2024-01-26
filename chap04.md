# Chapter 4

# Titrations Based on Acid-base Reactions

在很多教科书中，酸碱滴定也被称为是酸碱中和滴定，主要是因为多数情况下滴定过程完成之后，体系的pH值会向原来相反的方向发生改变。其中最简单的一个实例是氢氧化钠溶液滴定盐酸溶液。开始的时候，盐酸溶液呈现酸性，当加入等量的氢氧化钠溶液之后，整个体系的 pH 值变成 7.00 这个中性状态。当然，对于多数酸碱滴定体系而言，等量反应之后的 pH 值不会是 7.00,所以，中和反应这样的术语其实不太合适。

## 4.1 Proton theory of acid and base

## 4.2 Distributions of species in acid and base system

## 4.3 Calculation the concentration of hydrogen ion

## 4.4 Buffer solution of acid and base

## 4.5 Mathematical expressions of acid-base titration

### 4.5.1 Titration of hydrochloric acid solution with sodium hydroxide solution

The simplest titration example is the following:

$$
\mathrm{HCl(aq) + NaOH(aq) = NaCl(aq) + H_{2}O(l)   }
$$

Assume the initial concentration and volume of hydrochloric acid are $c(\mathrm{HCl})$ and $V(\mathrm{HCl})$, respectively; the initial concentration of sodium hydroxide is $c(\mathrm{NaOH})$. When $V(\mathrm{NaOH})$ volume of sodium hydroxide solution was added into the solution of hydrochloric acid, we get following mass balance equations:

$$
\begin{align*}
 \frac{c(\text{HCl})\times{}V(\mathrm{HCl})}{V(\mathrm{HCl})+ V(\mathrm{NaOH}) } 
&= [\text{Cl}^{-}] \tag{4.72} \\
 \frac{c(\text{NaOH})\times{}V(\mathrm{NaOH})}{V(\mathrm{HCl})+ V(\mathrm{NaOH}) }  
&= [\text{Na}^{+}] \tag{4.73}
\end{align*}
$$

The charged forms present during the titration process are $\mathrm{Na^{+}}$, $\mathrm{H^{+}}$, $\mathrm{OH^{-}}$ and $\mathrm{Cl^{-}}$. The charge balance between them is as follows:

$$
[\text{Na}^{+}] + [\text{H}^{+}] = [\text{OH}^{-}] + [\text{Cl}^{-}]
\tag{4.74}
$$

Substituting the terms from equations (4.72) and (4.73) into equation (4.74) yields:

$$
\frac{c(\text{NaOH})\times{}V(\mathrm{NaOH}) } {V(\mathrm{HCl})+ V(\mathrm{NaOH})} + [\text{H}^{+}] = [\text{OH}^{-}] + \frac{c(\text{HCl})\times{}V(\mathrm{HCl})}{V(\mathrm{HCl})+ V(\mathrm{NaOH})}
\tag{4.75}
$$

Define

$$
\eta = \frac{ V(\text{NaOH}) }{V(\text{HCl}) }, \quad 
\Delta = [\mathrm{H^{+}}] - [\mathrm{OH^{-} }  ]
$$

Rearranging equation (4.75) yields:

$$
\frac{c(\text{NaOH})\times{} \frac{V(\mathrm{NaOH})}{V(\mathrm{HCl})}  }
 {1+\frac{V(\mathrm{NaOH})}{V(\mathrm{HCl})} } 
+ [\text{H}^{+}] - [\text{OH}^{-}]= 
 \frac{c(\text{HCl})}
{1+\frac{V(\mathrm{NaOH})}{V(\mathrm{HCl})} }
$$

$$
\frac{c(\text{NaOH})\times{} \eta  }{1+\eta } 
+ \Delta =  \frac{c(\text{HCl})}{1+\eta }
$$

$$
c(\text{NaOH})\times{} \eta 
+ \Delta (1+\eta) =  c(\text{HCl}) 
$$

$$
c(\text{NaOH})\times{} \eta 
+ \Delta + \Delta\eta =  c(\text{HCl}) 
$$

$$
\left ( c(\text{NaOH}) +  \Delta \right )\times{} \eta 
=  c(\text{HCl}) - \Delta
$$

Thus,

$$
\eta=\frac{c(\text{HCl}) - \Delta}{c(\text{NaOH}) + \Delta} \tag{4.76}

$$

Equation (4.76) is the titration equation for titrating hydrochloric acid with sodium hydroxide. Due to the conjugate relationship between $\mathrm{H^{+}}$ and $\mathrm{OH^{-}}$, equation (4.76) is actually a quantitative relationship between volume ratio $\eta $ and hydrogen ion concentration $[\text{H}^{+}]$. By calculating the volume ratio at different hydrogen ion concentrations, a titration curve can be obtained as following

(Fig. 4.5 goes here)

The vertical axis on the titration curve is usually represented by the negative logarithmic value of hydrogen ion concentration (pH), which can better demonstrate the sharp decrease in hydrogen ion concentration.

---

## 4.6 Determination of Titration Endpoint and Titration Error

## 4.7 Typical applications

### 4.7.1 Measuring of nitrogen in organic

### 4.7.2 Measuring of nitrogen in ammonium salts

测定铵盐中的氮含量是酸碱滴定法一个非常经典的应用。

Nitrogen occurs in a wide variety of substances of interest in the life sciences, in industry, and in agriculture. Examples include amino acids, proteins, synthetic drugs, fertilizers, explosives, soils, potable water supplies, and dyes. Thus, analytical methods for the determination of nitrogen, particularly in organic substrates, are extremely important.

## 4.8 The Influence of Carbon Dioxide

---

Charles D. Winters T

Titration methods are based on de-
termining the quantity of a reagent of
known concentration that is required
to react completely with the analyte.
The reagent may be a standard solution
of a chemical or an electric current of
known magnitude.

In volumetric titrations, the volume
of a standard reagent is the measured
quantity.

In coulometric titrations, the quantity
of charge required to complete a reac-
tion with the analyte is the measured
quantity.
