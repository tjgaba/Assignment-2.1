# Sprint 1 Planning Session

- Date:           13 Jan 2026

- Sprint Goal:    Successfully confirm booking procurement by verifying on the main-system database, 
                  not just verification via the confirmation message sent to you. Note: Ask receptionist for 
                  double checking the booking on the dashboard.

## Attendees
- Product Owner: Bit Cube
- Scrum Master: TJ Gaba
- Development Team: Dev Team 1

## Velocity Target

**Time Coverage:**  

- 6 subtasks → 6 working days  
- 1 subtask can fit per day to cover the 6 day period.

**Total Story Points**  

- 2 + 1 + 2 + 1 + 1 + 1 = 8 sub-story points  
    - 8 ÷ 6 days = 1.33  sub-Sprint points per day needed to complete this story.
         - Velocity = 1.33 points per Sprint 

         - Rounded-off will be 2 -sub-points target per day. Therefore, this means  1 or possibly 2 subtasks can be done in one day to cover the main task's time of 6 days.

- But the fixed time per subtask/sub-sprint is 24hours each to cover the Fixed time for Sprint 1. So 8 / 2 points = 4 -sub-sprints, therefore there will be 4 sub-sprints in a span of 24 hours. 

Note: 
Fully aware that the above context (subtask/subpoint) 
is not part of the taught content, but added it for 
context and understanding. 

## Selected User Stories - (User subStories/subtask for Main-Sprint 1)

| Story # 			        | Title 				            | Story Points 	|
| [Story #1 - subtask 1] 	| Design booking data model 		| 2 		    |
| [Story #1 - subtask 2] 	| Implement availability check logic| 1 		    |
| [Story #1 - subtask 3] 	| Create booking API endpoint 		| 2 		    |
| [Story #1 - subtask 4] 	| Build booking UI component 		| 1 		    |
| [Story #1 - subtask 5] 	| Add validation and error handling | 1 		    |
| [Story #1 - subtask 6] 	| Write tests 				        | 1 		    |


## Dependencies

[Story #1 - subtask 1] - Design booking data model
- Blocked by -None 
- Blocking -[Story #1 - subtask 2]

[Story #1 - subtask 2] - Implement availability check logic
- Blocked by -[Story #1 - subtask 1] 
- Blocking -[Story #1 - subtask 3]

[Story #1 - subtask 3] - Create booking API endpoint
- Blocked by -[Story #1 - subtask 2] 
- Blocking -[Story #1 - subtask 4]

[Story #1 - subtask 4] - Build booking UI component
- Blocked by -[Story #1 - subtask 3] 
- Blocking -[Story #1 - subtask 5]

[Story #1 - subtask 5] - Add validation and error handling
- Blocked by -[Story #1 - subtask 4] 
- Blocking -[Story #1 - subtask 6]

[Story #1 - subtask 6] - Write tests
- Blocked by -[Story #1 - subtask 5] 
- Blocking -[Story #2] As an Employee, i  want to Select an automation option

## Risks
| Risk | Probability | Impact | Mitigation |

## Standup Cadence
Time:

Format: 
Yesterday 
Today
Blockers