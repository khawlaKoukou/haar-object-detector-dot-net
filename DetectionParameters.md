| **Parameter** | **Description** |
|:--------------|:----------------|
| MaxDetCount   | Detector stops searching when number of detected objects reaches this value. |
| MinNRectCount | Minimum neighbour areas must be passed the detector to verify existence of searched object. |
| FirstScale    | First scaler of searching window. |
| MaxScale      | Maximum scaler of searching window. |
| ScaleMult     | ScaleMult (Scale Multiplier) and current scaler are multiplied to make an increment on current scaler. |
| SizeMultForNesRectCon | SizeMultForNesRectCon (Size Multiplier For Nested Object Control) and size of every rectangle are multiplied separately to obtain maximum acceptable horizontal and vertical distances between current rectangle and others. Maximum distances are used to check if rectangles are nested or not. |
| SlidingRatio  | The ratio of step size to scaled searching window width. (CurrentStepSize = ScaledWindowWidth `*` SlidingRatio) |
| Pen           | A "Pen" object to draw rectangles on given bitmap. If it is given as null, nothing will be drawn. |