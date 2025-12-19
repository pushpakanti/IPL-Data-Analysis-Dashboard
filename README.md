# IPL Data Analysis Dashboard

## Overview

A comprehensive Power BI dashboard for analyzing Indian Premier League (IPL) cricket data, providing detailed insights into team performance, player statistics, season trends, and match analytics across 17 seasons (2008-2024) with 16 teams participating and 1,106 total matches.

## Dashboard Features

### 1. IPL Overview Page

The main dashboard page provides high-level statistics and trends.

**Key Metrics:**
- Total Seasons: 17 (2008-2025)
- Total Teams Participating: 16
- Total Matches: 1,106

**Key Visualizations:**

#### Top 10 Most Frequent Stadiums
Bar chart showing stadiums that have hosted the most IPL matches:
- Wankhede Stadium: 118 matches (highest)
- M. A. Chidambaram Stadium: 97 matches  
- Eden Gardens: 95 matches
- ARUN JAITLEY Stadium: 91 matches
- Feroz Shah Kotla: 85 matches

#### Sum of Noballs and Percentage of Wide Balls by Season
Line chart tracking:
- Total number of noballs across seasons
- Percentage of wide balls delivered
- Trend from 2008 to 2025 showing game evolution
- Notable peaks indicating rule changes or playing conditions

#### Average Runs Per Match (Season Wise)
Time series analysis showing:
- Trend from 2010 onwards
- Peak performance around 2020-2021 (175+ average)
- Fluctuations influenced by pitch conditions
- Current average runs per match analysis

#### Top 10 Most Frequent TV Umpires
Leaderboard featuring:
- Anil Chaudhary: 71 matches
- Sundaram Ravi: 65 matches
- Chaubey Shashank: 54 matches
- KN Ananthapad: 50 matches

#### Season-wise Quarter Rankings Table
Showing team dominance across quarters:
- Q.T_1 (First Quarter): Rajasthan Royals, Delhi Capitals, Mumbai Indians
- Q.T_2 (Second Quarter): Kings XI Punjab, Chennai Super Kings
- Q.T_3 (Third Quarter): Various team performances
- Q.T_4 (Fourth Quarter): Consistent leaders

### 2. Winner for Each Season Page

Detailed table showing champions across all 17 seasons:

**Notable Champions:**
- 2008: Rajasthan Royals (inaugural winner)
- 2009: Deccan Chargers  
- 2010-2011: Chennai Super Kings
- 2012-2014: Kolkata Knight Riders dominance
- 2015: Mumbai Indians
- 2016-2019: Multiple winners
- 2020: Mumbai Indians
- 2021-2025: Current season champions

Each entry includes:
- Season year
- Match ID and Match Name
- Home team and Away team
- Final winner details

### 3. Team Profile Page

Comprehensive team-level analytics including:
- Team statistics over all seasons
- Win-loss records
- Head-to-head matchups
- Performance trends

### 4. Player Profile Page

Individual player analytics featuring:
- Career statistics
- Batting and bowling performance
- Match participation records
- Performance metrics

## Data Insights

### Venue Analysis
- **Most Frequented Venues**: Mumbai's Wankhede Stadium leads with 118 matches
- **Geographic Distribution**: Cricket clubs across India host matches
- **Venue Impact**: Different stadiums show varying scoring patterns

### Temporal Trends
- **Scoring Evolution**: Average runs per match peaked in 2020-2021
- **Rule Changes**: Wide ball and noball percentages show evolution over years
- **Season Progression**: Clear trends in match outcomes across seasons

### Umpiring Analysis
- **Experienced Umpires**: Core set of 10 umpires officiate majority of matches
- **Match Distribution**: Umpires are distributed across venues and seasons

## Technologies Used

- **Power BI**: Interactive dashboard creation and visualization
- **Data Source**: IPL match and performance databases
- **Database**: SQL Server for data management
- **Analysis Tools**: DAX for complex calculations

## Dashboard Navigation

1. **Overview Tab**: Start here for high-level insights
2. **Season Winners**: Browse champions across years  
3. **Team Profile**: Analyze specific team performance
4. **Player Profile**: Explore individual player statistics
5. **Tooltips**: Hover over charts for detailed information

## Key Performance Indicators (KPIs)

- Total matches analyzed: 1,106
- Teams covered: 16
- Seasons analyzed: 17
- Data points: Millions of match events
- Umpires tracked: 10+ key officials

## Data Quality

- Comprehensive match-level data from all 17 IPL seasons
- Complete team and player statistics
- Accurate venue and umpire information
- Verified championship records

## Usage Instructions

1. Open the Power BI dashboard file (IPL_DASHBOARD.pbix)
2. Navigate between pages using tabs at the bottom
3. Use filters to customize views
4. Interact with visualizations for detailed breakdowns
5. Export reports as needed

## Future Enhancements

- Real-time data integration for live match updates
- Predictive analytics for match outcomes
- Player transfer analysis across seasons
- Advanced ML-based performance predictions
- Mobile-responsive dashboard versions
