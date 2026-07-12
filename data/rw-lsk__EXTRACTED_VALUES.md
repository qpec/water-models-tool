# LSK (Landelijke Steekproef Kaarteenheden) - extracted values
Source: Knotters, Hoogland & Brus 2013, Alterra-rapport 2440 "Validatie van grondwaterstandskaarten met de LSK"
Files: edepot_276389.pdf (Alterra-2440, 68pp), edepot_27713.pdf (Finke et al 2001 Status 2001), edepot_570308.pdf (nieuwe steekproefomvang C/bodemkwaliteit)

## Design / size
- LSK = gestratificeerd enkelvoudig aselecte steekproef; strata = bodemtype x grondwatertrap
- 1193 locations with GHG & GLG estimates (LSK-A random subsample)
- Missing GHG at 55 locations, missing GLG at 66 (stuwwallen/duinen -> deep water)
- LSK GHG max 357 cm; LSK GLG max 455 cm
- GxG estimated via stambuisregressie; sd of error 10-25 cm (Ritzema et al 2012)

## Gt (grondwatertrap) class boundaries (cm) - Tabel 2.2
Gt   GHG        GLG
I    <25        <50
II   <25        50-80
III  <25        80-120
IIIb 25-40      80-120
IV   40-80      80-120
V    <25        >120
Vb   25-40      >120
VI   40-80      >120
VII  80-140     >120
VIII >=140      >=180

## LSK-based validation of Gd-kaart (25x25 m)
- Gd-kaart resolution 25x25 m; GxG from 8-yr series ending 1997-2005
- GHG of Gd-kaart systematically shallower than LSK: mean diff 14 cm, median 7 cm
- GLG: no systematic difference
- Amplitude (GLG-GHG) Gd vs LSK (Tabel 3.14): ME -13(2) cm, RMSE 42, SDE 41, MAE 33; P2.5/P25/P50/P75/P97.5 = -94/-38/-15/6/74 cm
- vs NHI 3.0: GHG mean diff LSK-NHI = -22 cm, GLG = -17 cm (median both -7)
- vs Hydrologie Stone V2.3: GHG mean +13 (med 9), GLG +7 (med 7)

## Access status
- LSK point data GATED: input soil/GxG points require BRO/BIS credentials (basisregistratieondergrond.nl); privacy-restricted (confirmed via BIS-3D repo, Helfenstein et al).
- OPEN derivative: 4TU DOI 10.4121/16451739 "Tier 4 maps of soil pH 25 m NL" (BIS-derived, CC-BY 4.0, 43 GeoTIFFs, 3.37 GB) - uses BIS/LSK points but is a modelled product, not raw LSK.
