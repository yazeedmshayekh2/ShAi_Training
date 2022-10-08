our model should learn from classic dataset contains the prices and other attributes of almost 54,000 diamonds ,and be able to predict the diamond price . Features :

price : price in US dollars ($326--$18,823)

carat: weight of the diamond (0.2--5.01)

Carat is the unit of measurement for the physical weight of diamonds. One carat equals 0.200 grams or 1/5 gram and is subdivided into 100 points. For comparison, in units more familiar in the United States, one carat equals 0.007 ounce avoirdupois. Which would require over 2,265 carats to equal 1 pound!

cut :quality of the cut (Fair, Good, Very Good, Premium, Ideal)

The cut of a diamond refers to how well the diamond’s facets interact with light, the proportions of the diamond, and the overall finish of the diamond.

It is not to be confused with the shape, (like emerald or round,) or facet arrangement, (like brilliant, or step cut), but is instead a reference to the craftsmanship of the diamond and how it factors into the diamond’s brilliance.

![AGS Clarity Scale-1024x363](https://user-images.githubusercontent.com/102586302/194700452-6ac4ec12-eeaa-495f-9047-73ed738a9cd3.png)

color :diamond color, from J (worst) to D (best)

The Color of a diamond actually refers to the lack of color in a diamond, with perfectly colorless diamonds considered the highest quality with the highest value, and brown or yellow diamonds being the lowest quality.



clarity: a measurement of how clear the diamond is (I1 (worst), SI2, SI1, VS2, VS1, VVS2, VVS1, IF (best))

Clarity is the state of being clear or transparent. Diamond clarity is the presence or absence of characteristics called inclusions in the diamond.

When grading the clarity of a diamond, the lab determines the relative visibility of the inclusions in a diamond and their impact on the overall visual appearance.

So, what are these inclusions that affect clarity? In short, inclusions are the internal or external flaws of the diamond. The size and severity of these flaws determines the grade.

AGS Clarity Scale-1024x363.png

x :length in mm (0--10.74)

y :width in mm (0--58.9)

z :depth in mm (0--31.8)

depth :total depth percentage = z / mean(x, y) = 2 * z / (x + y) (43--79)

table :width of top of diamond relative to widest point (43--95)


