# Special Topics in Go for Finance
###### Last Updated: 12/28/2017

## Introduction
---
This course is a directed study between Jacob (Jake) Schurch and Professor Dave Louton. The course will occur throughout the winter semester of 2017/2018 and will replace the course requirement of taking FIN 370/380.


The course will focus on the student completing complex and elegant solutions (will be refered as _art projects_) in Go (also known as Golang) related to a **alGorithmic trading framework**. The overall deliverables will be highlighted [here](#Algorithmic-Trading-System-Module-Deliverables), and will be described semi-ambiguously until the beginning point of implementation. The reason being is _to allow for organic and agile development of the solution_. This allows for iterative prototyping and building of the _art projects_, hopefully creating a well-designed and achieving solution.


## Course Deliverables
---
#### Preface
Professor Louton and Jake will make contact at least once a week through Skype. During this time, the last week's module will be reviewed. Parameters for the upcoming week's module will be explored.

All materials will be hosted on the student's [Github](www.github.com) repo - allowing for continuous code integration/management of the framework. Each project will include a markdown file highlighting overall project contents/scope, how it was designed, results/outcome, concepts learned (as well as potentially other things) and if needed a changelog file.

### Algorithmic Trading System Module Deliverables
---
_(Broken up by module)_

0. Backtesting Environment Module
    - Be able to load a portfolio into backtest environment
    - Implement backtest environment using Monte Carlo Simulation
    - Be able to create market simulation scenarios, as well as specialized scenarios such as a downturn
    - Measure performance of a portfolio on a security level within  market simulation
2. Research System Modules
    - Be able to screen for securities based on security parameters
3. Portfolio Construction Module
    - Be able to add/drop (buy/sell) securities according to specified parameters/constraints
    - Implement a rule-based agent that will buy/sell securities
    - Implement a ML-based trading agent
3. Risk Management Module
     - Ability to set constraints/ strategy parameters on portfolio construction/optimization
     - Ability to measure portfolio metrics in a sandbox environment     
4. Execution System Module
    - Ability to take portfolio, set constraints and desired outcome, and implements a trading strategy within the backtested environment
    - Ability to take implemented trading strategy and apply it to a live trading market sandbox environment
    - Ability to process orders
5. Writeup on Code Profile, Lessons Learned, and Final Review of Directed Study

## Course Materials
---
- Reading material used may potentially include, but are not limited to:
  - Building Winning Algorithmic Trading Systems by Kevin J. Davey
  - Quantopian platform
  - Published articles regarding certain special topics
  - Lectures by Quantopian.com


  - Materials regarding optimization in Go
- Technical Materials Needed:
  - Go 1.x
  - Git & Github
  - Ubuntu stack (at least for student)

## Course Rubric
---
Due to the large level of implementing such a framework on one's own, **we are hoping to implement one module around ever 7-9 days.** Because uncertain circumstances/roadblocks may occur from implementing such a system framework, it will be at the discretion of Professor Louton to allow for any change in the syllabus to occur.

The student will be graded on each deliverable due to overall effort, timeliness of working implementation, design considerations, and completion of module functionality set out before implementation of the module.

### Grading Scheme
| Deliverable | Percent of Overall Grade |
| ----------- | ------------------------:|
| Module 0    | 10% |
| Module 1    | 15% |
| Module 2    | 20% |
| Module 3    | 20% |
| Module 4    | 30% |
| Module 5    | 5% |

[TOP](#Special-Topics-in-Go-for-Finance)
###### _written in boostnote editor_
