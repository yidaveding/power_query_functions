# power_query_functions
The Power Query Functions repo keeps some of the more commonly used power queries.

## createTable_WeeklyCalendarFlexible
This function generates a weekly calendar table based on the following input:
- startyear: first year in calendar, e.g. 2020. Calendar always starts on 1st Jan
- endyear: last year in calendar, e.g. 2024. Calendar always ends on 31st Dec
- financialYearStartMonth: first month of financial year, e.g. 7 in Australia, 4 in Japan
- WeekNumOfFirstMonday: 0 or 1. This allow you to adjust the starting point to shift back and forward by a week
