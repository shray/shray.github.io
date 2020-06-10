---
title: A Bayesian Framework for Nash Equilibrium Inference in Human-Robot Parallel Play
permalink: research/bayesnash/
layout: page
comments: false
---

 <img
    src="/assets/img/two_nash_ex.png"
    alt="Two Nash Equilibrium"
 />

We consider shared workspace scenarios with humans and robots acting to achieve independent goals, termed as parallel play. We model these as general-sum games and construct a framework that utilizes the Nash equilibrium solution concept to consider the interactive effect of both agents while planning. We find multiple Pareto-optimal equilibria in these tasks. We hypothesize that people act by choosing an equilibrium based on social norms and their personalities. To enable coordination, we infer the equilibrium online using a probabilistic model that includes these two factors and use it to select the robot's action. We apply our approach to a close-proximity pick-and-place task involving a robot and a simulated human with three potential behaviors - defensive, selfish, and norm-following. We showed that using a Bayesian approach to infer the equilibrium enables the robot to complete the task with less than half the number of collisions while also reducing the task execution time as compared to the best baseline. We also performed a study with human participants interacting either with other humans or with different robot agents and observed that our proposed approach performs similar to human-human parallel play interactions.  

<span style="color:red">Accepted at RSS 2020!</span>


<button>
	<a href="/assets/papers/bansal20bayesian.pdf">pdf</a>
</button>
<button>
	<a href="https://github.com/shray/bayes-nash">code</a>
</button>
<button>
	<a href="">arXiv</a>
</button>

<details>
	<summary>
		bibTeX
	</summary>
	<p>
	@inproceedings{bansal2020framework,  
  	title={A Bayesian Framework for Nash Equilibrium Inference in Human-Robot Parallel Play.},  
  	author={Bansal, Shray and Xu, Jin and Howard, Ayanna and Isbell, Charles},  
  	booktitle={Robotics: Science and Systems},  
  	year={2020}
	}
</p>
</details>