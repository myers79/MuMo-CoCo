# Change Log
All notable changes to the MuMoCoCo code will be documented in this file.
  
## 'Calculations' sheet - 2024-08-02
  
### Added
- Calculated Transit Time added; originally was located in 'Options' sheet cells AC3:4
- Capacity factor of 85% added to dehydration system
- Length of each interstate in each state added along with reference 62

### Removed
- Empty cell formatting removed
- Producer Price Index Data removed
- Cells CK179:CN229 deleted
 
### Fixed
- Heating requirement removed from reconditioning energy; assumed centrifugal pumping to supercritical condition
- Cell C177 calculation updated to include conditional based on the transport method; namely, rail or truck
- Cell B1168 corrected to account for the number of trucks and trailers that are sent to steel recycling

### Changed

## 'User Interface' sheet - 2024-08-02

### Added
- Added options for user to set storage time or use calculated time
- Added options for user to include/exclude costs of liquefaction and/or reconditioning

### Removed
-	Empty cell formatting removed

### Fixed

### Changed
-	D11, changed from “Results details” to “Cost details” 
-	Cell J23 updated to indicate whether rail transport is as a mixed use or unit train

## 'Options' sheet - 2024-08-02

### Added

### Removed
- Empty cell formatting removed

### Fixed

### Changed
-	AC3:4 (Calculated Transit Time) removed and replaced at Calculations B756. Connection to User Interface, User Inputs, cell B11 moved to Calculations B756.
-	Depreciation period expanded to 3–50 years
