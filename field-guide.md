# Read an area estimate without turning it into a promise

An area language estimate can suggest a question worth asking. It cannot tell you which language a particular visitor prefers, whether that person needs an interpreter, or which service your group should promise.

## 1. Keep the denominator attached

For Census table C16001, the population universe is people age five and over. The table concerns language spoken at home and English-speaking ability. That is different from total residents, event attendance, preferred written language, or demand for a specific activity. Record the original label and universe in the evidence register rather than shortening them to “language need.” See the [official C16001 metadata](https://api.census.gov/data/2024/acs/acs5/groups/C16001.html).

If the source presents a broad language group, preserve it as a group. Do not silently split it into individual languages or assume everyone in the group can use the same translated material.

## 2. Keep the geography attached

A ZIP Code Tabulation Area is a Census geography that approximates the distribution of postal ZIP codes. It is not a postal delivery route, and not every valid ZIP code has a corresponding ZCTA. Record `ZCTA`, the exact code and the relevant geography vintage when known. A county, city, ZCTA and service catchment are not interchangeable. The [Census ZCTA explanation](https://www.census.gov/programs-surveys/geography/guidance/geo-areas/zctas.html) describes the distinction.

Do not add overlapping areas together or describe a county figure as the count around one building. If your activity serves people from several areas, record that uncertainty instead of inventing a boundary crosswalk.

## 3. Preserve the period and source margin

An ACS five-year estimate describes a period, not a head count taken on today's date. Copy the survey period and table release. Record the retrieval date separately. Two files downloaded on the same day may describe different periods or geographies.

Published ACS margins of error use a 90% confidence level. Keep an estimate and its matching margin together, in the same units. A missing or annotated value is not zero. Record the original missing-value explanation instead of repairing it by guessing. Read the [Census comparison guidance](https://www.census.gov/help/topics/faq.do-i-need-to-consider-the-margins-of-error-when-comparing-acs-estimates.html) before making comparisons.

This workbook performs no statistical test, derived percentage margin, trend calculation or ranking. A larger point estimate alone does not establish a meaningful difference. Do not calculate a percentage's uncertainty by simply dividing the count margin by a denominator. If a comparison drives the decision, obtain an appropriate analysis using the source's current methodology, or leave that comparison undecided.

## 4. Keep responses separate from estimates

An optional listening exercise tells you what the respondents chose to share. It misses people who were absent, did not see the invitation, could not understand it, or chose not to answer. A tally of eight responses does not represent eight unique residents unless your collection method establishes that; this workbook intentionally avoids personal identifiers.

Record the invitation setting, collection method, language/format offered and known gaps. Do not multiply a response share by the area population. Do not infer citizenship, ethnicity, immigration status or household language from a response.

## 5. Require delivery evidence

For each proposed support option, record its actual format: a translated notice, a written outline, live interpreting and captions do different jobs. Confirm the relevant language variety, the responsible role and the material or equipment available. Record what was rehearsed and what has not been checked.

Use these decision states consistently:

| State | Meaning |
| --- | --- |
| PENDING | A required fact, agreement or check is missing. |
| READY FOR THIS ACTIVITY | The named support and fallback were checked for the specified activity. It is not a general quality certification. |
| NOT OFFERED | The team has decided not to promise this option for the activity; give a factual reason. |

Record a review date. A volunteer's availability, the activity format or participant requests can change the decision even when the area estimate is unchanged.
