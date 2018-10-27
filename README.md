# GRun
Configurable Garmin Watch datafield

![GRun Cover Image](/doc/GRunWatch.png) 

## Description
Highly configurable datafield where you can select up to 10 fields to display. If less fields are configured, the field area on each line will automatically expand.
The second and third row display a header field with the value. The Header fields can be positioned Top/Top, Top/Bottom or Bottom/Top.

The first, fourth and fifth row display values without header.

The following fields are currently supported:
- Empty
- Time
- Timer
- Time spend on current km/mile
- Last km/mile Time
- Distance
- Current Heart Rate
- Current Pace
- Current Speed
- Average Heart Rate
- Average Pace
- Average Pace (Calculated mnually using timer/distance)
- Average Speed
- Calories
- Current Cadence
- Altitude
- Total Ascent
- Total Descent
- Battery Icon
- GPS Icon
- GPS Icon & Battery Icon
- ETA 5K
- ETA 10K
- ETA Half Marathon (21.075.5 km)
- ETA Marathon (42.195 km)

## Notes
- Fields related to distance are displayed in km or mile depending on the user profile.
- Fields related to speed are displayed in km/h or mile/h depending on the user profile.
- Fields related to pace are displayed in min/km or min/mile depending on the user profile.
- Heart Rate is displayed in color based on user profile heart rate zone.
- Current Pace and Average Pace are displayed in color based on application parameters
  - Blue if too fast, Green if between Min and Max Pace, Red if too slow

## Configuration
### Header Position
Header Position can have 3 positions.
#### 1) Top / Top
![GRun TopTop](/doc/GRunWatch2.png)

#### 2) Top / Bottom
![GRun TopBottom](/doc/GRunWatch3.png)
#### 3) Bottom / Top
![GRun BottomTop](/doc/GRunWatch4.png)

### Less fields
If some fields are configured with option  **Empty**, the other fields on the same line will automatically expand. For example, the following screen is configured with **Field 2B = Empty**.

![GRun Expand](/doc/GRunWatch1.png)