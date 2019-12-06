# Mycroft Skills Data, v19.08

This repo holds data related to the Skills submitted and running on the
Mycroft system.  All data and scripts are available and usable under the
Apache 2.0 license.

Each branch of this repo holds information related to a single major
release of Mycroft Core.  This 19.02 branch only has information on Skills
submitted and running on Mycroft Core 19.02.xx systems.

## Skill Summary
The [skill-metadata JSON](https://github.com/MycroftAI/mycroft-skills-data/tree/19.02/skill-metadata.json)
contains a summary of all skills registered with the 19.02 branch of the
Mycroft-Skills repo.  It is regenerated regularly and can reliably be used for
things such as an available Skill browser.

The summary is generated by parsing the README.md for each skill.  Skill
authors should use the Meta Editor to ensure their README is parsable.

## Skill Usage Data
The [usage](https://github.com/MycroftAI/mycroft-skills-data/tree/19.02/usage)
section holds statistics generated from Mycroft users who have generously
decided to Opt In, allowing the community to learn from their participation. 

## Code
Python scripts used to create and/or analyze this data live under the
[scripts](https://github.com/MycroftAI/mycroft-skills-data/tree/19.02/scripts)
directory for each branch.
