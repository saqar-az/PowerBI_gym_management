# PowerBI gym management system
This project models a **gym club management system** where:
- Trainees are assigned to dedicated trainers.
- Trainers create personalized workout programs for each trainee.
- Trainees log their progress by marking completed exercises.
- Trainers provide feedback on trainee performance.
- Trainees adjust their programs based on feedback and continue until they reach their fitness goals.

---

## Database Schema

| Table | Description |
|-------|-------------|
| User | All users (athletes, coaches, admins) |
| AthleteProfile | Athlete-specific goals & metrics |
| Exercise | exercise list |
| WorkoutPlan | Training programs per athlete |
| PlanDays | Session order within a program |
| PlanExercises | Exercise details per session |
| WorkoutLogs | Athlete exercise logs |
| Feedbacks | Coach feedback messages |
| Ratings | Athlete ratings for coaches |
| AthleteProfile_History` | Historical progress tracking |

---

## PowerBI Reports

- **Report 1: Coach Performance Dashboard**
Evaluate coach performance based on their interactions with athletes.

- **Report 2: Athlete Consistency Dashboard**
Track athlete program completion and activity levels.

- **Report 3: Club Status Dashboard**
Provide a snapshot of overall club performance.

- **Report 4: At-Risk Athlete Identification**
Identify athletes at risk of performance decline or dropout.

- **Report 5: Athlete Goal Achievement**
Track athlete progress toward their fitness goals.
