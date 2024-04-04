# Code Learning
## env
### base
#### *base_task.py*
* ``class BaseTask() -> as model``

#### *legged_robot.py*
* ``class LeggedRobot(BaseTask) -> main part of scripts ``
  * ``compute_observations(self) -> torch.cat all the obs``
  * ``step(self, actions) -> step simulation``
> Q1:heading_command? 
> Q2:where read urdf model?
### cassie(or diy)

## utils
### *task_registry.py*
* ``class TaskRegistry()``
  * ``make_alg_runner(self,**)``
## tests
## scripts
