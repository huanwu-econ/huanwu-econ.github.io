---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

<head>
  <meta charset="UTF-8">
  <title>Katex</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/katex@0.11.1/dist/katex.min.css" integrity="sha384-zB1R0rpPzHqg7Kpt0Aljp8JPLqbXI3bhnPWROx27a9N0Ll6ZP/+DiW/UqRcLbRjq" crossorigin="anonymous">
  <script defer src="https://cdn.jsdelivr.net/npm/katex@0.11.1/dist/katex.min.js" integrity="sha384-y23I5Q6l+B6vatafAwxRu/0oK/79VlbSz7Q9aiSZUvyWYIYsd+qj+o24G5ZU2zJz" crossorigin="anonymous"></script>
  <script defer src="https://cdn.jsdelivr.net/npm/katex@0.11.1/dist/contrib/auto-render.min.js" integrity="sha384-kWPLUVMOks5AQFrykwIup5lo0m3iMkkHrD0uJ4H5cjeGihAutqP0yW0J6dpFiVkI" crossorigin="anonymous" onload="renderMathInElement(document.body);"></script>
</head>



<br>

# Job Market Paper
***

## [Unobserved Heterogeneous Spillover Effects in Instrumental Variable Models](https://huanwu-econ.github.io/files/JMP_Wu.pdf)

<details open>
   <summary><u>Abstract</u></summary>
   <p>This paper develops a general framework for identifying causal effects in settings with spillovers, where both outcomes and endogenous treatment decisions are influenced by peers within a known group. It introduces <i>the generalized local average controlled spillover and direct effects</i>, which extend the local average treatment effect framework to spillover settings and establish general conditions for their point identification. These conditions formally justify the use of additional restrictions, such as one-sided noncompliance, to achieve point identification with binary instruments in related studies. The paper then defines <i>the marginal controlled spillover and direct effects</i>, which naturally extend the marginal treatment effect framework spillover settings and are nonparametrically point identified from continuous instrumental variation. These marginal effects serve as building blocks for a broad class of policy-relevant treatment effects, including local average spillover and direct effects studied in the related work. The paper develops semiparametric estimators and establishes their asymptotic properties, and further proposes a parametric approach for practical implementation. An application using Add Health data illustrates the framework and reveals heterogeneity in educational spillovers within best-friend networks.
</p>
</details> <br> 


<br>

# Working Papers
***

## [Testing Identifying Assumptions in Parametric Separable Models: A Conditional Moment Inequality Approach](https://huanwu-econ.github.io/files/GKW-2024.pdf) 
with [Leonard Goff](https://www.leonardgoff.com/) and [Désiré Kédagni](https://sites.google.com/site/desirekedagni/)

<details>
    <summary><u>Abstract</u></summary>
    <p>In this paper, we propose a simple method for testing identifying assumptions in parametric separable models, namely treatment exogeneity, instrument validity, and/or homoskedasticity. We show that the testable implications can be written in the intersection bounds framework, which is easy to implement using the inference method proposed in Chernozhukov, Lee, and Rosen (2013), and the Stata package of Chernozhukov et al. (2015). Monte Carlo simulations confirm that our test is consistent and controls size. We use our proposed method to test the validity of some commonly used instrumental variables, such as the average price in other markets in Nevo and Rosen (2012), the Bartik instrument in Card (2009), and the test rejects both instrumental variable models. When the identifying assumptions are rejected, we discuss solutions that allow researchers to identify some causal parameters of interest after relaxing functional form assumptions. We show that the IV model is nontestable if no functional form assumption is made on the outcome equation, when there exists a one-to-one mapping between the continuous treatment variable, the instrument, and the first-stage unobserved heterogeneity.
    </p>
</details> <br> 

## [Robust Identification in Randomized Experiments with Noncompliance](https://huanwu-econ.github.io/files/KWC-2025.pdf) 
with [Désiré Kédagni](https://sites.google.com/site/desirekedagni/) and Yi Cui

<details>
    <summary><u>Abstract</u></summary><p> 
    Instrument variable (IV) methods are widely used in empirical research to identify causal effects of a policy. In the local average treatment effect (LATE) framework, the IV estimand identifies the LATE under three main assumptions: random assignment, exclusion restriction, and monotonicity. However, these assumptions are often questionable in many applications, leading some researchers to doubt the causal interpretation of the IV estimand. This paper considers a robust identification of causal parameters in a randomized experiment setting with noncompliance where the standard LATE assumptions could be violated. We discuss identification under two sets of weaker assumptions: random assignment and exclusion restriction (without monotonicity), and random assignment and monotonicity (without exclusion restriction). We derive sharp bounds on some causal parameters under these two sets of relaxed LATE assumptions. Finally, we apply our method to revisit the random information experiment conducted in Bursztyn, González, and Yanagizawa-Drott (2020) and find that the standard LATE assumptions are jointly incompatible in this application. We then estimate the robust identified sets under the two sets of relaxed assumptions.
</p>
</details> <br> 



# Work In Progress
***

## Identifying One-way Spillover Effects in Randomized Experiments
with [Désiré Kédagni](https://sites.google.com/site/desirekedagni/)

<details>
    <summary><u>Abstract</u></summary><p>   
	In this paper, we consider the identification of one-way spillover effects in a randomized experiment where we observe different groups of individuals. In each group, some individuals are randomly assigned a treatment, while the remaining individuals do not receive the assignment directly. However, the decision/behavior and outcome of those who do not receive the treatment may be influenced by their treated peers. Individuals who are assigned the treatment are the "leaders," while those who do not receive the treatment but may be exposed to its effects are referred to as "followers." We are interested in identifying the causal effects of a leader’s treatment on her follower’s outcome. To do so, we introduce the concepts of local average controlled spillover effects (LACSE) and local average controlled direct effects (LACDE). We reformulate the identification problem as a two-component mixture problem. This allows us to derive sharp bounds for these parameters by employing Lee’s (2009) trimming strategy. Furthermore, we demonstrate how our framework can be applied to a randomized experiment with imperfect compliance in which the instrument could potentially violate the exclusion restriction. Finally, we propose estimation and uniform inference results for the identified sets.
</p>
</details> <br> 

## Treatment Effects with a Misreported Outcome
with [Désiré Kédagni](https://sites.google.com/site/desirekedagni/)

<details>
    <summary><u>Abstract</u></summary><p>   
	In this paper, we discuss some identification issues that arise in policy evaluation when the outcome variable is misreported. We show that when the outcome of interest is binary and misclassified in a randomized experiment with perfect compliance, the difference-in-means estimand identifies a weighted average treatment effect for people who misreport and those who do not, with a negative weight for the former group. This negative result extends to randomized experiments with imperfect compliance. We show that the availability of multiple exogenous data sources can help partially identify treatment effects for the correctly reporting and misreporting groups separately. We generalize our identification results to any real-valued outcomes. We demonstrate how the knowledge of the direction of misreporting could help tighten the identified set. 
</p>
</details> <br> 

## Relaxing Identifying Assumptions in Triangular Model
