# Open Source Contributions

A portfolio of my contributions to open-source projects.

## OpenTracks OSM Plugin - Map Legend Feature

**Project**: [OpenTracks](https://github.com/OpenTracksApp/OpenTracks) - Android app for GPS tracking  
**Issue**: [#67 - Implement Map Legend](https://github.com/OpenTracksApp/OpenTracks/issues/67)  
**Role**: Team Lead & Core Developer  
**Date**: 2023

### Overview
Led the implementation of a map legend feature that displays color-coded speed visualization 
for recorded GPS tracks in the OpenTracks Android application.

### My Contributions
- **Technical Leadership**: Analyzed dashboardapi codebase, mapped dependencies across multiple 
  teams, and coordinated parallel development efforts
- **Architecture**: Designed baseline speed calculation system (average/max speed) for polyline 
  color mapping
- **Implementation**: Developed conditional rendering logic for legend visibility based on 
  'Color by Speed' setting
- **Collaboration**: Created and managed sub-issues, conducted code reviews, and maintained 
  issue tracker updates

### Technical Stack
- **Language**: Java (Android)
- **Components**: MapsActivity.java, TrackPoint.java, map.xml
- **Tools**: Android Studio, Git/GitHub, Issue Tracking

### Code Analysis
Assigned codebase: `src/main/java/de/storchp/opentracks/osmplugin/dashboardapi`

The dashboardapi module provides classes and methods for interacting with OpenTracks' core 
data structures (tracks, track points, waypoints). Key responsibilities included:
- Query and retrieval of recorded track data
- Statistical calculations on GPS track points
- Waypoint handling from Geo URIs

### Challenges Overcome
1. **Cross-team Coordination**: Managed dependencies and communication across 5+ teams working 
   on interconnected features
2. **Data Flow Analysis**: Traced complex dependencies between map rendering, track statistics, 
   and user settings
3. **Conditional Logic**: Implemented dynamic legend rendering based on application state

### Impact
Successfully delivered feature enhancing user experience for GPS tracking visualization, 
merged into main branch serving 1,000+ GitHub stars and active user base.

## Future Contributions
Actively seeking opportunities to contribute to data engineering, analytics, and 
visualization open-source projects.
