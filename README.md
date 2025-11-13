⚾ MLB Swing-and-Miss Analysis (2025 Season)
Project Overview
This Excel-based project explores the relationship between swing-and-miss rate (Whiff%) and offensive performance (OPS) for all qualified MLB hitters from the 2025 season. The goal is to understand how often missing pitches impacts total offensive output — and to identify players who balance power and contact most efficiently.
________________________________________
Objectives
	Analyze whether lower Whiff% correlates with higher OPS.
	Develop a new metric, Whiff Efficiency (WE), to measure offensive productivity relative to swing-and-miss rate, with additional weight given to power production.
	Use Excel visualization tools (scatterplots, correlation functions) to reveal patterns and outliers among hitters.
________________________________________
Custom Metric: Whiff Efficiency (WE)
Definition:
Whiff Efficiency quantifies how effectively a hitter converts offensive potential into production relative to how often they swing and miss — now weighted to favor players who produce higher OPS values. This version rewards power hitters who maintain strong offensive output even with elevated swing-and-miss rates.
Formula:
(OPS^3 ÷ Whiff%) × 100
Example:
If a player has an OPS of 0.850 and a Whiff% of 20%,
then
WE=((0.850)^3)/0.20×100=307.1

A higher WE indicates a player who generates elite offensive output relative to their swing-and-miss rate, with increased emphasis on power performance.
________________________________________
Data & Methods
	Data Source: MLB Statcast (Baseball Savant) – 2025 Qualified Batters
	Tools Used: Microsoft Excel
	Steps:
	Imported player data (OPS and Whiff%) into Excel.
	Created a scatterplot with Whiff% (x-axis) and OPS (y-axis).
	Calculated the correlation coefficient (r = 0.247) to assess the relationship.
	Computed Whiff Efficiency (WE) for each player using the OPS³ adjustment.
	Highlighted notable players and trends on the scatterplot using labeled data points.
________________________________________
Key Findings
	The correlation (r = 0.247) suggests a weak positive relationship — players who swing and miss slightly more often may also generate more power.
	Using the OPS³ formula gives additional weight to power hitters, improving representation for sluggers who trade some contact for extra-base strength.
	Players like José Ramírez, Geraldo Perdomo, and Jacob Wilson still show strong efficiency through balanced contact, while Kyle Schwarber and Aaron Judge rise in ranking under the adjusted metric.
	Whiff Efficiency (OPS³-based) serves as a valuable comparative tool for understanding how contact and power interact in offensive success.
________________________________________
Future Improvements
	Extend analysis across multiple MLB seasons to track consistency of Whiff Efficiency.
	Incorporate ISO and Barrel% to further refine how power is quantified.
	Compare Whiff Efficiency among player archetypes (contact hitters, sluggers, balanced hitters).
	Visualize data using regression lines or trend zones to illustrate efficiency tiers.
