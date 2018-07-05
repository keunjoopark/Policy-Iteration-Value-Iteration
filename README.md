# Policy-Iteration-Value-Iteration


* Policy Iteration: perform policy evaluation and policy improvement iteratively until find to optimal policy

* Value Iteration: policy evaluation is stopped after just few sweep (one update of each state) instead of doing multiple steps of policy evaluation

* Difference between policy iteration and value iteration: Value Iteration is simillar with policy iteration to control. However, value iteration uses max instead of using argmax to update in synchronous backup. So, it does not require to policy update every time (There is no explict policy). Thus, value iteration is faster to convergence than policy iteration sometimes.



