# ERD
**Developing Entity Relationship Diagram**

A company has several departments. Each department has a supervisor and
at least one employee. Employees must be assigned to at least one, but
possibly more departments. At least one employee is assigned to a project,
but an employee may be on vacation and not assigned to any projects. The
important data fields are the names of the departments, projects, supervisors
and employees, as well as the supervisor and employee number and a unique
project number.

From the description of the problem we see that:
* Each department has exactly one supervisor.
* A supervisor is in charge of one and only one department.
* Each department is assigned at least one employee.
* Each employee works for at least one department.
* Each project has at least one employee working on it.
* An employee is assigned to 0 or more projects.



![ERD drawio](https://github.com/lasyaEd/ERD/assets/163686352/879206aa-dc82-40c8-a478-800114fddc7b)
