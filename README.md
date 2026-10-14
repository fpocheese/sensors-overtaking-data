# Overtaking Figure Data and Video

Figure data and a demonstration video accompanying the manuscript:

**Robust Stackelberg-Supervised Overtaking Policy with Persistent Tactical Corridors for Autonomous Racing**

## Contents

All data and the video are in [`data_sensors_processed_cases`](data_sensors_processed_cases/).

- Yas Marina: four case files.
- Imola: four case files.
- Suzuka: four case files.
- `Fig10.csv`: the case illustrated in Figure 10.
- [`overtake.mp4`](data_sensors_processed_cases/overtake.mp4): demonstration video.

## CSV format

Each CSV contains the final plotting coordinates used in the manuscript figures.

| Column | Meaning |
| --- | --- |
| `figure` | Manuscript figure number |
| `panel` | Panel letter |
| `series` | Curve, point set, boundary, or surface component |
| `point` | Point order within the series |
| `x`, `y` | Horizontal and vertical plotting coordinates |
| `z` | Third coordinate for 3D data; blank for 2D data |

Units follow the corresponding manuscript axes. Select a figure, panel, and series, then plot the coordinates in point order. For example, `Fig6 / c / ego_speed` uses time in `x` and ego speed in `y`.

The coordinates are ready to plot without further smoothing, rescaling, or interpolation. The original figure styling and simulator screenshots are separate from these numerical coordinates.
