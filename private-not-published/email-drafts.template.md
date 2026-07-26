# Sanitized Email Draft Templates

> **Privacy warning:** This folder is excluded from navigation on GitHub Pages, but the repository is public, so this file remains publicly readable on GitHub. Copy this file to `email-drafts.local.md` for private edits. Files ending in `.local.md` are excluded by `.gitignore`.

## Dr. Ariane Middel

**Subject:** Intersection waiting exposure and modular shade research

Dear Dr. Middel,

My name is Robert Lehr, and I am a PhD student in Sustainable Systems Engineering at The University of Texas at Austin. My research examines pedestrian thermal exposure at signalized intersections and whether modular engineered shade can function as a measurable transportation, public-health, and urban-resilience intervention.

I have been reviewing your work on pedestrian-scale thermal exposure, shade typologies, MaRTy, and Cool Routes. My reading of the published Cool Routes methodology is that cumulative thermal exposure is primarily represented as distance-weighted MRT along pedestrian-network edges. I did not see corner-specific pedestrian signal delay, stationary exposure at waiting areas, or arrival-dependent waiting time explicitly represented. Is that interpretation accurate, or does the current implementation account for signalized-intersection delay in a way not described in the publication?

I am considering an extension that treats each signalized corner as a time-dependent thermal-exposure node. The model would combine corner-level MRT or UTCI with pedestrian arrival time, signal timing, expected waiting duration, waiting position, and counterfactual shade geometry. The aim is to test whether including waiting exposure changes route recommendations and identifies intersections where added shade yields the greatest reduction in cumulative person-time exposure.

The proposed research program includes Austin intersection screening, field measurement, behavioral observation, standards review, lifecycle cost analysis, and a temporary modular shade pilot. I am also requesting design and evaluation data from Phoenix regarding its artistic shade structures at intersections.

Would you be willing to recommend methodological cautions, datasets, or publications that should shape this work? I would also value your assessment of whether signalized-intersection waiting environments remain a meaningful gap in current thermal-routing research.

Best,
Robert Lehr
PhD Student, Sustainable Systems Engineering
The University of Texas at Austin

## Dr. Dev Niyogi and UT Austin team

**Subject:** Extending CoolPath to include signalized-intersection waiting exposure

Dear Dr. Niyogi and team,

I am developing research on pedestrian thermal exposure at signalized intersections, with particular attention to time spent waiting at exposed corners and the potential effect of modular shade interventions.

In reviewing the published CoolPath methodology, I understand that candidate routes are evaluated using UTCI sampled along route geometry. Although route duration is available as metadata, I did not see intersection-specific waiting time, pedestrian signal timing, or stationary corner exposure explicitly included in the thermal objective. Is that interpretation correct?

I am considering a complementary module that represents signalized intersections as time-dependent exposure nodes. It would combine corner-level thermal conditions with signal-cycle data, pedestrian arrival timing, expected delay, crossing time, waiting position, and shade geometry. This would allow the model to ask both which route is coolest and where an intervention would create the largest reduction in cumulative person-time exposure.

I would appreciate any guidance on the current model architecture, available Austin thermal layers, route data, or methodological constraints that would affect such an extension. I am also interested in whether this could complement the team’s current work rather than duplicate it.

Best,
Robert Lehr

## Phoenix staff data request

**Subject:** Data request regarding Phoenix artistic sidewalk shade structures

Dear [Name / Team],

I am a PhD student at The University of Texas at Austin researching pedestrian thermal exposure and shade interventions at signalized intersections. Phoenix’s artistic sidewalk shade structures appear to be one of the most direct municipal precedents for this work.

Could your team share any available information on: site-selection criteria; exact locations and corner placement; drawings and dimensions; capital and maintenance costs; solar or shadow studies; thermal measurements; pedestrian counts; waiting-location behavior; crossing compliance; conflicts or safety observations; accessibility and visibility review; maintenance, vandalism, and wind performance; public feedback; and any planned or completed evaluation?

I am particularly interested in whether the structures’ shadows overlap actual pedestrian waiting areas during the hottest high-use periods and whether before-and-after behavioral or safety data were collected.

I would cite the City and relevant project staff in any resulting research product and would be glad to share a concise summary of findings.

Best,
Robert Lehr
