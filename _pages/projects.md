---
layout: archive
title: "Projects & Publications"
permalink: /projects/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %}

## Publications
**Streaming Services and Multilevel Conversion Journeys**\
with David Rothschild and Elad Yom-Tov\
Currently under review at Marketing Science, Preprint available on [SSRN](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4627170), 2023

_Abstract:_ We investigate the online user conversion funnel as it pertains to streaming video services. We provide a snapshot of current advertising strategies undertaken by streaming services on search engines and attempt to explain user behavior through the standard conversion funnel model. We find that the marginal lift for streaming advertisements is greater on queries that are not highly targeted and that a majority of user search sessions do not reflect sequential movements through stages of the conversion funnel. Additionally, short search sessions and the limited number of streaming queries per user hinder the applicability of the standard conversion funnel in explaining user behavior. We supplement our analysis by clustering users based on their streaming search history and identify salient archetypes that match the heterogeneity that we see in the data well. Finally, we propose a more generalized, multilevel conversion journey model that reflects our key findings and provides a clearer picture of user exploration. We discuss how different conversion journeys can be reconstructed from this model, providing a framework for stakeholders to better understand key questions (e.g., divergent pricing models, market consolidation, exclusivity of content) in large and growing industry in flux.

**Soft Actor-Critic Solution to a Security Game with Deception and An Informant**\
with Jinhong Guo, Martin Hofmann, Carter Veldhuizen, and Valerie Champagne\
26th International Command and Control Research and Technology Symposium, 2021

_Abstract:_ In this paper, we describe an application of deep reinforcement learning to a security game. We model competition between two opponents as a two-player game with an added third-party player and solve for the optimal strategy using deep reinforcement learning to approximate the game equilibrium, yielding courses of action (COAs) for the attacker and defender that anticipate and respond to the opponent’s actions. Solving multi-agent security games with a meta strategy-guided Deep Reinforcement Learning algorithm yields robust, explainable decision support and reduces the risk of surprise due to unexpected adversary COAs. Our approach learns an effective defender strategy despite the attacker blending into the background population modeled by the third-party player, and exploits the third-party player as an unreliable informant.

_Citation:_ J. K. Guo, M. O. Hofmann, C. Veldhuizen, S. Satya, and V. Champagne, Soft Actor-Critic Solution to a Security Game With Deception and an Informant, 26th International Command and Control Research and Technology Symposium, 2021.

## Projects
**A Contest Model of Talking and Listening (in progress)**\

_Description:_ Ongoing work started in my second year at Microsoft Research, supervised by Dr. Markus Möbius.

_Current Abstract:_ Advances in communication technology have increased the effective sizes of meetings. Online meetings enable more participants to join and asynchronicity (such as SMS chat groups) amplifies this effect further. Through a simple model in which agents compete in a winner-take-all contest for a prize that scales with the size of the network, I investigate how the cost of communication, network size, and asymmetries in baseline speaking qualities between conversation participants might contribute to participation inequality. I first identify a unique mixed strategy Nash equilibrium in contests where all agents are symmetric in their average speaking quality. I then highlight an equilibrium strategy profile in contests with asymmetric agents whereby agents with the highest baseline speaking qualities will always choose to talk and all others will choose to listen. I conclude by extending the analysis in (Schaffer, 1988) to finite contests with asymmetric agents and present computational results that suggest conditions under which this equilibrium is both unique and evolutionarily stable.

[Current Version](https://sidsatya.github.io/files/microbroadcasters_writing_sample.pdf)

**Estimating the Impact of Artificial on Jobs Within the Healthcare Industry (revision in progress)**\

_Description:_ My senior thesis, completed at UC Berkeley under the guidance of Professor Enrico Moretti.

_Abstract:_ The rapid growth of the artificial intelligence field, as well as its ability to impact nearly every economic sector, underscores the importance of understanding its potential impact on labor. This paper examines how wages and employment levels for jobs in the healthcare industry are affected by artificial intelligence as well as the net effect of two direct impacts of AI through a difference-in-differences approach.  The results show that wages and employment for Physicians and Surgeons increased after the introduction of IBM Watson for healthcare applications in 2013 while no significant effect was found for Secretaries and Administrative Assistants in the healthcare industry. Overall, the results suggest that when artificial intelligence augments labor on decision tasks, it has a net positive effect whereas the effect of AI on the automation of prediction tasks remains ambiguous. 

[Current Version](https://sidsatya.github.io/files/senior_thesis.pdf)
