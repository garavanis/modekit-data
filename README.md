# modekit-data

Example data for [modekit](https://github.com/garavanis/modekit). The example
notebooks download the files they need from here on their first run
(`modekit.datasets.fetch`); there is no need to clone this repository.

| Folder | Contents |
| --- | --- |
| [`heartspace`](heartspace) | Tap tests and fan-excited records of the aluminium GARTEUR structure: healthy, damaged and restored. See its README. |

Each CSV is one test set, tab-separated: the sample rate [Hz] on the first line,
the column names (`<channel>_tap_<rep>`) on the second, the units on the third,
then the samples.
