# PortfolioProjects
## Here you will come a cross to different projects like: 
    Maji Ndongo (national water survey) - POWER BI
    Data professinals survey - POWER BI
    Bike sales - Excel

## Maji Ndongo (national water survey)

Project Objective
The government of Maji Ndogo has collected data on water sources across the country. I was tasked to build a Power BI dashboard that:

        Identifies which citizens lack access to basic water.
        Diagnoses the problem (Pollution? Broken infrastructure? Long wait times?).
        Calculates a budget to fix these issues (typically capped around $147 Million).
        Tracks the progress of the engineering teams fixing the sources.


1. The Core Problem: Water Source Breakdown

The analysis reveals that the population relies on five distinct water sources, each with specific failures:
        
        Rivers (Rural Crisis): A significant portion of the rural population relies on open rivers. The water quality is extremely poor, leading to high health risks.
        Action: These people need groundwater wells drilled imm[1][2]ediately.
        Shared Taps (Urban Crisis): While the water quality here is good, the access is the issue. The data shows massive overcrowding.
        Finding: 43% of the population relies on these, but wait times frequently exceed 120 minutes.
        Action: Install more taps near existing ones to reduce wait times to under 30 minutes.
        Wells (Contamination): Many wells are functionally working but pump unsafe water.
        Finding: Distinct split between Clean, Biologically Contaminated, and Chemically Contaminated wells.
        Action: Install UV filters for biological issues and Reverse Osmosis (RO) filters for chemical issues.
        Tap in Home (Infrastructure Failure): A large percenta[4]ge of homes have plumbing installed, but the taps are "Broken."
        Action: These are the cheapest fixes; they simply require maintenance teams to repair the existing infrastructure.

2. Geographical Disparities (Province Analysis)

        The dashboard highlights that the water crisis is not evenly distributed across the five provinces:
        Sokoto: This is the most critical province. It is largely rural, relies heavily on rivers/wells, and requires the largest share of the budget for drilling             new wells.
        Kilimani: A more urban province. The main issue here is typically Shared Tap overcrowding and queue times.
        Amanzi: Often shows high rates of pollution in existing water sources, requiring a focus on filtration rather than drilling.
        3. The "Gender Gap" in Water Collection
        Finding: By analyzing the demographic data combined with queue times, the dashboard reveals that women and children bear the primary burden of water                     collection.
        Impact: The 2+ hour wait times at Shared Taps are directly removing women from the workforce and children from school.

4. Financial Summary (The Budget)

        Using DAX measures to calculate the cost of fixing each specific source, the project usually concludes with the following financial requirements:
        Total Budget Required: Approximately $147 Million (varies slightly based on currency conversion in the specific course version).
        Allocation:
        The most expensive line item is Drilling New Wells (replacing rivers).
        The second most expensive is installing RO Filters (cleaning polluted wells).
        The cheapest high-impact solution is repairing broken home taps.

5. The "Corruption" Insight (Project Extension)

        In the final stages of the project (often involving SQL and Power BI validation), an audit analysis reveals:
        Discrepancies: There are records where the reported water source improvement does not match the actual engineer's log.
        The Culprit: Visuals often point to specific officers (e.g., an employee frequently associated with high-cost, verified-false entries) suggesting embezzlement or             data fraud.
