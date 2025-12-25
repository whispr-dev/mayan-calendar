[README.md]

# Mayan-Calendar

<p align="center">
  <a href="https://github.com/whisprer/mayan-calendar/releases"> 
    <img src="https://img.shields.io/github/v/release/whisprer/mayan-calendar?color=4CAF50&label=release" alt="Release Version"> 
  </a>
  <a href="https://github.com/whisprer/mayan-calendar/actions"> 
    <img src="https://img.shields.io/github/actions/workflow/status/whisprer/mayan-calendar/lint-and-plot.yml?label=build" alt="Build Status"> 
  </a>
</p>

![Commits](https://img.shields.io/github/commit-activity/m/whisprer/mayan-calendar?label=commits) 
![Last Commit](https://img.shields.io/github/last-commit/whisprer/mayan-calendar) 
![Issues](https://img.shields.io/github/issues/whisprer/mayan-calendar) 
[![Version](https://img.shields.io/badge/version-3.1.1-blue.svg)](https://github.com/whisprer/mayan-calendar) 
[![Platform](https://img.shields.io/badge/platform-Windows%2010%2F11-lightgrey.svg)](https://www.microsoft.com/windows)
[![Python](https://img.shields.io/badge/python-3.8%2B-blue.svg)](https://www.python.org)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

<p align="center">
  <img src="mayan-calendar-banner.png" width="850" alt="Mayan-Calendar Banner">

# mayan_calendar
 code to tell the date in mayan calendar

202502080103 Sat.

this was started 05, Wed. originally an exercise/excuse in learning to code in `Rust`, it turned into my greatest labour of love so far. i guess i can sum up the kinda project this has been overall in one wonderful example:
i was battling why on earth i could only get the Haab glyph to display and not the Tzolk'in in the midst of my final run through optimization and near the finish line when finally i found the problem - the `.png` file containing the glyph image for the days date, i thought Tzolk'in day 'Chuwen', it turned out, midnight having passed 5mins previously, meant that it wzas now Tzolk'in day 'Eb'. unfortunately my file had been naamed as the alternate naming/pronunciation of 'En'. this meant the file had a dif name to that which the script was trying to reference and hence waasn't being found. DOH! ...and this is just a microcosm of the way the entir project ahs been from the get go. hilariously filled with silly false starts, errors, gotchas and gah!'s.

anyways, it's now down from a peak of near 1000lines of one huge code file to a nice 500line main.rs and a coupla external modules/config files. everythings fantastically neatly organised and laid out within the code, it runs so lightly task manager cant even detect it and it actually does what it says on the tin - i.e. display the date in gregorian and mayan calendaar as numbers/mayan numerals and mayan libroglyphs, and also has a realtime clock and astronomical info as relevant to the day.

i should point out i did sleep twice during the 3 days i spent coding this - so i only did maybe 3x 20hr stints at it total separated by a coupla sleeps. :P
