# Arsenal-Squad-Shooting-Stats-23-24
this dataset contains shot statistics of arsenal players for the season 2023/24
## **Context**
this dataset contains shot statistics of arsenal players for the season 2023/24

Player: The name of the player.

Nation: The name or abbreviation of the player's country.

Pos: The position the player plays (e.g., Forward, Midfielder, Defender).

Age: The age of the player.

90s: The number of minutes the player has played in terms of 90-minute units. This represents the total amount of time played converted into 90-minute segments.

Gls: The total number of goals scored by the player.

Sh: The total number of shots taken by the player.

SoT: The number of shots on target by the player (shots that are on goal).

SoT%: The percentage of shots on target by the player. Calculation: (SoT / Sh) * 100.

Sh/90: The average number of shots per match by the player. Calculation: Sh / 90s.

SoT/90: The average number of shots on target per match by the player. Calculation: SoT / 90s.

G/Sh: The average number of goals per shot by the player. Calculation: Gls / Sh.

G/SoT: The average number of goals per shot on target by the player. Calculation: Gls / SoT.

Dist: The average distance of the player’s shots (typically measured from the goal).

FK: The number of goals scored from free kicks by the player.

PK: The number of goals scored from penalties by the player.

PKatt: The number of penalties taken by the player.

xG: The expected goals of the player. This metric measures the probability of a shot resulting in a goal, accounting for the quality of the chances.

npxG: The expected goals of the player excluding penalties. This calculates xG without considering penalty shots.

npxG/Sh: The ratio of expected goals excluding penalties per shot by the player. Calculation: npxG / Sh.

G-xG: The difference between the goals scored and the expected goals. Calculation: Gls - xG. This shows how much more or less the player has scored compared to the expected goals.

np
: The difference between non-penalty goals and expected goals. Calculation: Gls - npxG. This shows how much more or less the player has scored in open play compared to the expected goals.
