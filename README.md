# golf-scorecard
A scorecard for (disc) golf. 

/Courses/
create as you go, don't have to set up before playing the round
save to central database to link to and load from the app
default settings of 9 and 18 holes

/Players/
create as you go, enter at the start of a round
save a profile to email results
possible integration with handicap calculator

/Rounds/
The main thing that is edited during play
Header: course, date
Items: players, holes, scores, par
need a central place to save everything

/About/
details of app and development

works offline - don't need connectivity for capture, but do need for saving
              - email facility for sending results (likely google drive format)
              
spreadsheet representation of a round, header, plus holes by players

database representation of a round
1. roundid, hole, playerid, score
2. roundid, courseid, playerid
3. playerid, name, email

/Handicap/
round is assessed for handicap or not
ability to alter final scores for a round vs handicap
summary screen for a round to manually enter handicap

But also, UDisc
