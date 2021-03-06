---
layout: page
title: Research
permalink: /research/
---

The PI’s research philosophy is to conduct research that has theoretic foundation and impact on emerging social networking research and wireless network standards. In recent years, the PI focuses on network simulation platform, game theoretic model for wireless networks, and social learning framework for social networks. The aim of our research is to achieve both academic value and industrial impact.

# Novel Learning-based Framework for Rational Sequential Decision Making in Wireless and Social Networks with Practical Applications

Traditionally, the network configuration and management problem are usually treated as optimization problems. The system status and resources are treated as constraints with all configurable parameters and actions of users as decision variables in a snapshot. This approach relies on assumptions that the status of the system is known and remains unchanged, and all decision variables can be controlled by the network managers or operators at the same time. These assumptions are impractical in real world networks where network status and users constantly change, and each user makes their decision on their own willingness, at different timing, with different amount of knowledge. The traditional snapshot approach will lead to poor performance in these networks. In this work, we aim to design general decision making frameworks to properly capture these new characteristics in order to improve the system performance and prediction accuracy.

We present Chinese Restaurant Game, a novel approach to analyze and manage the users in the networks in light of these observations. The users in the network are assumed to be rational and make decisions sequentially with asymmetric information. They learn the information from observed signals or actions, and response to the state changes to maximize their own utilities. We explore this new research direction under a series of game-theoretic frameworks. The frameworks can capture all settings we mentioned above, help us predict the decisions of users in the network, and provide management tools to regulate them to improve the performance. We also provide both in-depth theoretic analysis and share our experience in data-driven experimental results on various applications. This work has been documented in several top-tier journals:

> [J1]       Chih-Yu Wang, Yan Chen, K.J. Ray Liu, “Game-Theoretic Cross Social Media Analytic: How Yelp Ratings Affect Deal Selection on Groupon?,” IEEE Transactions on Knowledge and Data Engineering, volume 30, number 5, pages 908-921, May 2018.
>
> [J2]       Chih-Yu Wang, Yan Chen, K.J. Ray Liu, “Hidden Chinese Restaurant Game: Grand Information Extraction for Stochastic Network Learning,” IEEE Transactions on Signal and Information Processing over Networks, volume 3, number 2, pages 330 - 345, June 2017.
>
> [J3]       Yan Chen, Chunxiao Jiang, Chih-Yu Wang, Yang Gao, K. J. Ray Liu,”Decision Learning: Data Analytic Learning with Strategic Decision Making,” IEEE Signal Processing Magazine, volume 33, number 1, pages 37-56, ﻿Jan. 2016.
>
> [J4]       Biling Zhang, Yan Chen, Chih-Yu Wang, K.J. Ray Liu,”A Chinese Restaurant Game for Learning and Decision Making in Cognitive Radio Networks,” Computer Networks, volume 91, pages 117-134, ﻿Nov. 2015.


# Cutting-Edge Research on D2D Communications in Fifth-Generation (5G) for Projected Commercial Launch of 5G in 2020


The development of fifth major generation (5G) mobile communication aims at not only just an improvement from 4G in terms of speed, but also a comprehensive solution for various new applications such as Internet of Thing, Tactile Internet, and other novel applications with very diverse and challenging requirements. Key techniques have been developed to achieve these technical goals. For instance, device-to-device (D2D) communications enables end devices to communicate with each other directly instead of relaying through base stations. This boosts up the transmission speed when the devices are in proximity. Nevertheless, the local transmission scheme also suggested that selfish users may overuse this technique like we have observed in Wi-Fi networks. In this work, we aim to propose Novel solutions to guarantee the overall system performance while prevent users from overuse the new techniques.

We developed several novel game theoretic solutions for D2D communication to achieve optimal system configuration with self-organized manners. Users will switch to D2D communication only if he is willing to pay a payment decided by the service provider. The payment serves as a regulation tool for the service provider to manage the demands of users. We discuss how the payment can be decided in order to achieve optimal system performance while preventing the users from overuse or underuse the D2D communications. The optimal configuration of D2D communications can be achieved with proper pricing strategy. The performance improvement is also verified with simulations. This work has been documented in top-tier journals:

> [J5]       Yi Zhang, Chih-Yu Wang, Hung-Yu Wei, “Incentive Compatible Overlay D2D System: A Group-Based Framework without CQI Feedback,” IEEE Transactions on Mobile Computing, volume 17, number 9, pages 2069-2086, Sep. 2018
>
> [J6]       Shih-Tang Su, Bo-Yuan Huang, Chih-Yu Wang, Che-Wei Yeh, Hung-Yu Wei, “Protocol Design and Game Theoretic Solutions for Device-to-Device Radio Resource Allocation,” IEEE Transactions on Vehicular Technology, volume 66, number 5, pages 4271 - 4286, May 2017.

# Cutting-Edge Research on Internet of Things in Fifth-Generation (5G) for Projected Commercial Launch of 5G in 2020

Internet of Things is expected to be the next killing application of 5G networks and the enabler of smart home/city, vehicle/industrial automations, e-health, etc. Nevertheless, most existing or currently developing IoT communication standards, including Narrow-Band IoT in 3GPP LTE-Advanced, are based on the assumption that IoT services only require low data rate transmission and therefore can be supported by limited resources such as narrow-band channels. This assumption rules out those IoT services with burst traffic, critical missions, and low latency requirements. We aim to propose a novel solution to break this limitation while compatible with existing or developing IoT protocols.

We propose to utilize idle devices in IoT networks to boost the transmission data rate for critical tasks through multiple concurrent transmissions. This approach virtually expands the existing narrow-band IoT protocols to break the bandwidth limitation in order to provide low latency services for critical tasks. We theoretically prove that the optimal relay configuration that minimizes the uploading latency in single source scenario can be derived by the proposed algorithms in polynomial time. The simulation results show that the proposed approach can reduce the latency of critical tasks up to 76% comparing with traditional approaches. This work has been documented in top-tier journal and conference:

> [J7]       Shang-Hong Hsu, Chi-Han Lin, Chih-Yu Wang, Wen-Tsuen Chen, “Breaking Bandwidth Limitation for Mission-Critical IoTs using Semi-Sequential Multiple Relays,” IEEE Internet of Things Journal (IF:5.863), accepted (DOI:10.1109/JIOT.2017.2776403)
>
> [C1]     Shang-Hong Hsu, Chih-Han Lin, Chih-Yu Wang, W. T. Chen, “Minimizing Upload Latency for Critical Tasks in Cellular-based IoT Networks using Multiple Relays,” IEEE International Conference on Communications (ICC), Paris, France, May 2017.

# Industrial Collaboration with Oath Taiwan on E-commerce Query Forecasting System

Search has been a critical function in e-commerce websites as it serves as one of the main entry points leading to shopping transactions. Nevertheless, performing search function is costly to a large e-commerce website. An unoptimized search function may generate poor results to mislead the customer, and therefore increases the length of the search session or even loses this transaction. Thus, it is important to optimize the search function in order to provide smooth search experience and meaningful results so customers can find the product in the process with minimum cost to the website. Our technical goals in this collaboration are two folds: 1) predicting the subsequent queries and final queries given the current profile of the customer and early queries, and 2) identifying critical queries at the early stage of a search session and redirect the users to these queries as early as possible.

We establish a Query Forecasting System which not only predicts the subsequent queries based on the initial queries and but also provides an adjustment function to estimate the impact of the query results and refine the suggestions according to the goal of the e-commerce vendor. With the collaboration with Oath (Yahoo!) Taiwan, we collect and analyze the e-commerce search history of Yahoo users. The amount of daily search queries is in millions on average, generated by around a million of active users. We also validate our assumptions and perform experiments on real e-commerce search system. The developed techniques in this work have been progressively transferred to Oath Taiwan and are deployed in production.
