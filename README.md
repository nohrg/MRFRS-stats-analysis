# MRFRS-stats-analysis
Statistical analysis for a cat shelter. Phase 1 Project for DS 5500 Fall 2025

Merrimack River Feline Rescue Society, a cat shelter based in Salisbury MA, wants to know which of its event types has been most successful at getting cats adopted, as well as any patterns in successful (and unsuccessful) applications from potential adopters. Most of what they've worked off of has been gut feeling, rather than getting their decisions supported by their own data.

Using their data from 2021 to the present, I intend to answer their questions and hypotheses around two topics: adoption demographic and success patterns, and cat outcomes. This will be done primarily with traditional statistical analysis and turned into a report for the MRFRS staff. I will consider the project successful if I can provide effective and expressive visualizations and analysis for the major questions of each topic.

Dataset:
- Intake data: intake date, animal ID, animal name, species, primary breed, sex, altered, intake type, intake sub-type, intake by, intake from (ID), intake from name
- Outcome data: outcome date, outcome time, animal ID, animal name, species, primary breed, sex, altered, intake type, outcome type, outcome sub-type, outcome to (ID), outcome to name, outcome by
- Hard-to-place cats: animal ID, animal name, attributes
- Length of stay: animal ID, animal name, species, primary breed, date of birth, age group at intake, current status, current location, intake date, intake type, outcome date, outcome type, days in custory, days onsite, days available
- Adopter support: date of adoption, animal ID, animal name, species, primary breed, sex, altered, estimated birthdate, microchip number, by (user), outcome subtype, adopter ID, adopter name, city, state, zip

Data notes:
- Intake by/outcome by [intake/outcome data]: staff member ID
- Intake from (ID)/intake from name [intake data]: source of cat (eg. the trapper who caught the cat, another animal welfare organization)
- Outcome to (ID)/outcome to name [outcome data]: adopter or other person responsible for the cat (in cases of non-adoption outcomes)
- By (user) [adopter support]: staff member ID
