Homework(Chapeter 5)
================

5.1

<table>
<colgroup>
<col width="17%" />
<col width="32%" />
<col width="32%" />
<col width="17%" />
</colgroup>
<thead>
<tr class="header">
<th>Description</th>
<th>Receive Payment at Time</th>
<th>Pay Security at Time</th>
<th>Payment</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Outright sale</p></td>
<td><pre><code>      0</code></pre></td>
<td><pre><code>       0</code></pre></td>
<td><p>S<sub>0</sub><span class="citation">@0</span></p></td>
</tr>
<tr class="even">
<td><p>Fully Leveraged Sale</p></td>
<td><pre><code>      T</code></pre></td>
<td><pre><code>       0</code></pre></td>
<td><p>S<sub>0</sub>e<sup>rT</sup><span class="citation">@T</span></p></td>
</tr>
<tr class="odd">
<td><p>Prepaid Forward Contract</p></td>
<td><pre><code>      0</code></pre></td>
<td><pre><code>       T</code></pre></td>
<td><pre><code>    ?</code></pre></td>
</tr>
<tr class="even">
<td><p>Forward Contract</p></td>
<td><pre><code>      T</code></pre></td>
<td><pre><code>       T</code></pre></td>
<td><p>?e<sup>rT</sup></p></td>
</tr>
</tbody>
</table>

5.2.1

$$
50-\\sum\_{i=1}^{4}{e\_i^rT}
$$

$50 - \\sum\_{i=1}^4 e\_{i}^{rT}$

50 − *e*<sup>0.06 \* 0.25</sup> − *e*<sup>0.06 \* 0.5</sup> − *e*<sup>0.75 \* 0.06</sup> − *e*<sup>0.06</sup> = 46.1458

### 5.2.2

46.1458 \* *e*<sup>0.06</sup> = 48.9993

### 5.3.1

50 \* *e*<sup>−0.08</sup> = 46.15

### 5.3.2

46.15 \* *e*<sup>0.06 − 0.08</sup> = 45.2362

### 5.4.1

35 \* *e*<sup>0.025</sup> = 35.88

### 5.4.2

1/*T* \* ln(*F*<sub>0, *T*</sub>/*S*<sub>0</sub>)

### 5.4.3

1.  *F*<sub>0, *T*</sub><sup>*P*</sup> = *S*<sub>0</sub>*e*<sup>(*r* − *δ*)*T*</sup> = 35 \* *e*<sup>0.025</sup> = 35.88
2.  
    1/*T* \* ln(*F*<sub>0, *T*</sub>/*S*<sub>0</sub>)=2ln(35.5/35)=0.028369
     Sub 1 into 2, then we get:
    1/*T* \* ln(*S*<sub>0</sub>*e*<sup>(*r* − *δ*)*T*</sup>/*S*<sub>0</sub>)
    1/*T* \* ln*e*<sup>(*r* − *δ*)*T*</sup>
    1/*T* \* (*r* − *δ*)*T*
    *r* − *δ* = 0.028369
    *δ* = 0.05 − 0.028369 = 0.021631

### 5.6.1

*S*<sub>0</sub>*e*<sup>(*r* − *δ*)*T*</sup> = 1100*e*<sup>(0.05 − 0.015)3/4</sup> = 1129.26

### 5.6.2

<table style="width:94%;">
<colgroup>
<col width="36%" />
<col width="27%" />
<col width="30%" />
</colgroup>
<thead>
<tr class="header">
<th align="center">Description</th>
<th align="center">Today</th>
<th align="center">In 9 months</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="center">Long Forward</td>
<td align="center">0</td>
<td align="center"><span class="math inline"><em>S</em><sub><em>T</em></sub> − <em>F</em><sub>0, <em>T</em></sub></span></td>
</tr>
<tr class="even">
<td align="center">Sell short the index</td>
<td align="center">$+S_{0}e^{T}</td>
<td align="center">$ <span class="math inline">−<em>S</em><sub><em>T</em></sub></span></td>
</tr>
<tr class="odd">
<td align="center">Lend<span class="math inline">−<em>S</em><sub>0</sub><em>e</em><sup><em>δ</em></sup></span></td>
<td align="center">$-S_{0}e^{T}</td>
<td align="center">$ <span class="math inline"><em>S</em><sub>0</sub><em>e</em><sup>(<em>r</em> − <em>δ</em>)<em>T</em></sup></span></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col width="30%" />
<col width="29%" />
<col width="40%" />
</colgroup>
<thead>
<tr class="header">
<th align="center">Description</th>
<th align="center">Today</th>
<th align="center">In 9 months</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="center">Long Forward</td>
<td align="center">0</td>
<td align="center"><span class="math inline"><em>S</em><sub><em>T</em></sub> − <em>F</em><sub>0, <em>T</em></sub></span></td>
</tr>
<tr class="even">
<td align="center">Sell short the index</td>
<td align="center"><span class="math inline">+1100<em>e</em><sup>−0.015 * 0.75</sup></span></td>
<td align="center"><span class="math inline">−<em>S</em><sub><em>T</em></sub></span></td>
</tr>
<tr class="odd">
<td align="center">Lend<span class="math inline">−<em>S</em><sub>0</sub><em>e</em><sup><em>δ</em></sup></span></td>
<td align="center"><span class="math inline">−1100<em>e</em><sup>−0.015 * 0.75</sup></span></td>
<td align="center"><span class="math inline"><em>S</em><sub>0</sub><em>e</em><sup>(<em>r</em> − <em>δ</em>)<em>T</em></sup></span></td>
</tr>
<tr class="even">
<td align="center">Total</td>
<td align="center">0</td>
<td align="center"><span class="math inline"><em>S</em><sub>0</sub><em>e</em><sup>(<em>r</em> − <em>δ</em>)<em>T</em></sup> − <em>F</em><sub>0, <em>T</em></sub> = 0</span></td>
</tr>
</tbody>
</table>

### 5.6.3

<table>
<colgroup>
<col width="32%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Description</p></td>
<td><pre><code>     Today</code></pre></td>
<td><pre><code>    In 9 months</code></pre></td>
</tr>
<tr class="even">
<td><p>Short Forward</p></td>
<td><pre><code>          0</code></pre></td>
<td><pre><code> $F_{0,T}-S_{T}$</code></pre></td>
</tr>
<tr class="odd">
<td><p>Sell long the index</p></td>
<td><pre><code> $-S_{0}e^{\delta T}$</code></pre></td>
<td><pre><code>     $S_{T}$</code></pre></td>
</tr>
<tr class="even">
<td><p>Borrow<span class="math inline">−<em>S</em><sub>0</sub><em>e</em><sup><em>δ</em></sup></span></p></td>
<td><pre><code>$+S_{0}e^{\delta T}$</code></pre></td>
<td><p><span class="math inline">−<em>S</em><sub>0</sub><em>e</em><sup>(<em>r</em> − <em>δ</em>)<em>T</em></sup></span></p></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col width="32%" />
<col width="29%" />
<col width="37%" />
</colgroup>
<thead>
<tr class="header">
<th align="center">Description</th>
<th align="center">Today</th>
<th align="center">In 9 months</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="center">Short Forward</td>
<td align="center">0</td>
<td align="center"><span class="math inline"><em>F</em><sub>0, <em>T</em></sub> − <em>S</em><sub><em>T</em></sub></span></td>
</tr>
<tr class="even">
<td align="center">Sell long the index</td>
<td align="center"><span class="math inline">−<em>S</em><sub>0</sub><em>e</em><sup><em>δ</em><em>T</em></sup></span></td>
<td align="center"><span class="math inline"><em>S</em><sub><em>T</em></sub></span></td>
</tr>
<tr class="odd">
<td align="center">Borrow<span class="math inline">−<em>S</em><sub>0</sub><em>e</em><sup><em>δ</em></sup></span></td>
<td align="center"><span class="math inline">+<em>S</em><sub>0</sub><em>e</em><sup><em>δ</em><em>T</em></sup></span></td>
<td align="center"><span class="math inline">−<em>S</em><sub>0</sub><em>e</em><sup>(<em>r</em> − <em>δ</em>)<em>T</em></sup></span></td>
</tr>
<tr class="even">
<td align="center">Total</td>
<td align="center">0</td>
<td align="center"><span class="math inline"><em>F</em><sub>0, <em>T</em></sub> − <em>S</em><sub>0</sub><em>e</em><sup>(<em>r</em> − <em>δ</em>)<em>T</em></sup> = 0</span></td>
</tr>
</tbody>
</table>

### 5.7.1

*S*<sub>0</sub> = 1100, *r* = 5, *δ* = 0
*F*<sub>0, *T*</sub> = 1100 \* *e*<sup>0.05 \* 0.5</sup> = 1127.85

1135 &gt; 1127.85 So, we should sell forward and buy S&R index.

<table>
<colgroup>
<col width="32%" />
<col width="29%" />
<col width="37%" />
</colgroup>
<thead>
<tr class="header">
<th align="center">Description</th>
<th align="center">Today</th>
<th align="center">In 9 months</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="center">Short Forward</td>
<td align="center">0</td>
<td align="center"><span class="math inline">1135 − <em>S</em><sub><em>T</em></sub></span></td>
</tr>
<tr class="even">
<td align="center">Sell long the index</td>
<td align="center">-1100</td>
<td align="center"><span class="math inline"><em>S</em><sub><em>T</em></sub></span></td>
</tr>
<tr class="odd">
<td align="center">Borrow<span class="math inline">−<em>S</em><sub>0</sub><em>e</em><sup><em>δ</em></sup></span></td>
<td align="center">+1100</td>
<td align="center">-1127.85</td>
</tr>
<tr class="even">
<td align="center">Total</td>
<td align="center">0</td>
<td align="center">7.15</td>
</tr>
</tbody>
</table>

The profit is 1135 − 1127.85 = 7.15

### 5.7.2

<table>
<colgroup>
<col width="30%" />
<col width="29%" />
<col width="40%" />
</colgroup>
<thead>
<tr class="header">
<th align="center">Description</th>
<th align="center">Today</th>
<th align="center">In 9 months</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="center">Long Forward</td>
<td align="center">0</td>
<td align="center"><span class="math inline"><em>S</em><sub><em>T</em></sub> − 1115</span></td>
</tr>
<tr class="even">
<td align="center">Sell short the index</td>
<td align="center">+1100</td>
<td align="center"><span class="math inline">−<em>S</em><sub><em>T</em></sub></span></td>
</tr>
<tr class="odd">
<td align="center">Lend<span class="math inline">−<em>S</em><sub>0</sub><em>e</em><sup><em>δ</em></sup></span></td>
<td align="center">-1100</td>
<td align="center">+1127.85</td>
</tr>
<tr class="even">
<td align="center">Total</td>
<td align="center">0</td>
<td align="center">$1127.85-1115=12.85</td>
</tr>
</tbody>
</table>

### 5.8.1

*F*<sub>0, *T*</sub> = 1100*e*<sup>(0.05 − 0.02)\*0.5</sup> = 1166.12

<table>
<colgroup>
<col width="32%" />
<col width="29%" />
<col width="37%" />
</colgroup>
<thead>
<tr class="header">
<th align="center">Description</th>
<th align="center">Today</th>
<th align="center">In 9 months</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="center">Short Forward</td>
<td align="center">0</td>
<td align="center"><span class="math inline">1120 − <em>S</em><sub><em>T</em></sub></span></td>
</tr>
<tr class="even">
<td align="center">Sell long the index</td>
<td align="center"><span class="math inline">−1100<em>e</em><sup>−0.01</sup></span></td>
<td align="center"><span class="math inline"><em>S</em><sub><em>T</em></sub></span></td>
</tr>
<tr class="odd">
<td align="center">Borrow<span class="math inline">−<em>S</em><sub>0</sub><em>e</em><sup><em>δ</em></sup></span></td>
<td align="center"><span class="math inline">+1100<em>e</em><sup>−0.01</sup></span></td>
<td align="center">-1116.12</td>
</tr>
<tr class="even">
<td align="center">Total</td>
<td align="center">0</td>
<td align="center">3.88</td>
</tr>
</tbody>
</table>

### 5.8.2

<table>
<colgroup>
<col width="30%" />
<col width="29%" />
<col width="40%" />
</colgroup>
<thead>
<tr class="header">
<th align="center">Description</th>
<th align="center">Today</th>
<th align="center">In 9 months</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="center">Long Forward</td>
<td align="center">0</td>
<td align="center"><span class="math inline"><em>S</em><sub><em>T</em></sub> − 1110</span></td>
</tr>
<tr class="even">
<td align="center">Sell short the index</td>
<td align="center"><span class="math inline">+1100<em>e</em><sup>−0.01</sup></span></td>
<td align="center"><span class="math inline">−<em>S</em><sub><em>T</em></sub></span></td>
</tr>
<tr class="odd">
<td align="center">Lend<span class="math inline">−<em>S</em><sub>0</sub><em>e</em><sup><em>δ</em></sup></span></td>
<td align="center"><span class="math inline">−1100<em>e</em><sup>−0.01</sup></span></td>
<td align="center">+1116.12</td>
</tr>
<tr class="even">
<td align="center">Total</td>
<td align="center">0</td>
<td align="center"><span class="math inline">1116.12 − 1110 = 6.12</span></td>
</tr>
</tbody>
</table>

### 5.9.1

*r* = 12.5, *S*<sub>0</sub>*e*<sup>0.125</sup>

So, we should travel to 1981 to invest at 12.5% and travel to mature date to collect the money

### 5.9.2

The interest rate will go down when bringing large amount of money because this will increase the quantity of cash in market.

### 5.9.3

The time travel will cause massive amount of money, which means investors will bring much more money than before to get profit.

### 5.11.1

250 \* 4 \* 1200 = 1, 200, 000

### 5.11.2

1, 200, 000 \* 0.1 = 120, 000

### 5.15.1

Cash and Carry: 800*e*<sup>0.055</sup> = 845.2324

Cash and carry arbitrage: 800*e*<sup>0.05</sup> = 841.0168

### 5.15.2

Cash and Carry: (800 + 1)*e*<sup>0.055</sup> = 846.2890

Cash and carry arbitrage: (800 − 1)*e*<sup>0.05</sup> = 839.9656

### 5.15.3

Cash and Carry: (800 + 2.4 + 1)\**e*<sup>0.055</sup> = 848.8247

Cash and Carry arbitrage: (800 − 2.4 − 1)\**e*<sup>0.05</sup> = 837.4425

### 5.15.4

Cash and Carry: (800 + 2.4 + 1)\**e*<sup>0.055</sup> + 2.4 = 850.9097

Cash and Carry arbitrage: (800 − 2.4 − 1)\**e*<sup>0.05</sup> − 2.4 = 834.76

### 5.15.5

Cash and Carry: (800 \* 1.003 + 800 \* 0.003 + 1)\**e*<sup>0.055</sup> = 851.3604

Cash and Carry arbitrage: (800 \* 0.997 − 800 \* 0.003 − 1)\**e*<sup>0.05</sup> = 834.9195

### 5.16.1

875 \* *e*<sup>0.0475</sup> = 917.5645

### 5.16.2

Value: 250 \* 875 = 218750

800000/218750 = 3.657142
*β* = 1.1 &gt; 1
 So, 3.657142 \* 1.1 = 4.0228
