# Pomodoro

Question (medium)

Pomodoro
Read about Pomodoro here.


https://en.wikipedia.org/wiki/Pomodoro_Technique <br>
Task: create a Pomodoro timer <br>
staff-solution: https://5fd46f0a8fce2146cd8899b8--goofy-bell-f5c7c2.netlify.app/

Acceptance Criteria


All buttons should have following attributes respectively

• Set data-testid='set-btn'

• Start data-testid='start-btn'

• Stop data-testid='stop-btn'

• Reset data-testid='reset-btn'



• Should have two INPUT-FIELDS with following attributes

• First one for Work-Duration data-testid='work-duration'

• Second one for Break-Duration data-testid='break-duration'



• User should not able to set negative value for work-duration and break-duration

Should be able to Enable / Disable buttons as demonstrated in staff's solution

Render Break-Time / Work-Time on screen as per requirement and clock-time

Once clock started it's never stop unless user forcefully stop it.

Should be able to switch between Work-Time to Break-Time and vice-versa. (Basically Loop work-time and break-time)

Should be able to alert once Break-Time / Work-Time finishes. use alert()

Work-duration or Break-duration could be zero 0, but can not set to 0 both Work-Duration and Break-Duration simultaneously. If uses forcefully does so, then set to default values of work-duration and break-duration

Note: Work-Duration default value is 25. Break-Duration default value is 5
