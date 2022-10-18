FinalProject_Yan
================
Yan
2022-10-17

## Abstract

## Introduction

Fringing reefs are widely distributed in the tropical and subtropical
zones across the world. The structure of fringing reefs provide the
habitats for the intertidal and subtidal organisms (*Menard et al. 2012*
\[^1\]). Meanwhile, the morphology of fringing reefs are shaped by the
reef-building organisms and the environment factors (*Duce et al. 2016*
\[^2\]). Previous researches have studied the growth and morphology of
fringing reefs from geology aspect (*Kennedy and Woodroffe 2002* \[^3\])
and the bathymetric distribution of corals on the fringing reefs (*Dai
1993* \[^4\]). But the connection between biodiversity and morphology of
fringing reefs and their geographical differences has not been studied.

Fringing reefs can be easily observed from the satellite images in
Google Earth. The differences of fringing reefs can be observed along
the latitude (*Fig 1.*) or the different side of island. In this
project, we would quantify several morphological traits of fringing
reefs and try to explore their connection with environmental factors and
biology. The spurs and grooves are the most distinct features in the
fringing reefs.

We are going to answer following questions:

1.  How is the **morphology of fringing reefs** distributed
    geographically? What are the differences along the latitude?

2.  Is the morphology of fringing reefs correlated with the
    **biodiversity**?

3.  What is the **relation** between morphology of fringing reefs,
    biodiversity and environmental conditions?

## Method

選19個，測站跨越南北半球，緯度介於南瑋23\~北緯26之間 biogeographic
realm在中西太平，測站是有完整的天然礁岩海岸的小島或環礁
根據緯度絕對值將測站排序依次命名，刪掉其中一個槽溝太寬的離群值 股哥地球
高解析度衛星圖 ，套入ARCGIS PRO， 線圖徵計算 群礁的型態 槽溝長 寬
密度、海岸寬、海岸粗糙度 水溫資料來自ARCGIS的資料庫 溫度是2010
2月及9月的平均
生物資料來自RLS，固定深度在3<sub>8間，調查月份6</sub>9月年份在2009、2012、2014、2015，時間在11:00\~15:00

用R做相關性分析

## Result

結果 我們的測站SST和緯度的相關性，SST會影響礁體，對密度的影響最為明顯

槽溝長和群礁寬有相關 槽溝與群礁越長越寬 生物總數越少

生物量和型態的關係是最不明顯的，可能是因為生物量的測量方法是用估計的關係，所以不是很準確

平均體型在漕溝寬度和密度有相反的關係，越密集體型越小(體型與緯度越高也有相關性)，越寬體型越大

## Discussion

討論 密度影響明顯的原因可能是高緯的礁體容易破碎
