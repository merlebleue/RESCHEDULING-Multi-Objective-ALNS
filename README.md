# Developping an Adaptive Large Neighborhood Search heuristic, for multiple objectives.

> Semester project in [Transp-OR](https://www.epfl.ch/labs/transp-or/) laboratory at EPFL.
> 
> Author: Julien ARS in spring 2025, under the supervision of Léa Ricard and Prof. Michel Bierlaire.

In this project, I developped an ALNS heuristic for use in railway rescheduling. It was part of a larger project for use in the RER Vaud under 3 different objectives (passenger cost, operator cost and deviation from the original timetable). The focus was on large disruptions, such as a track closure for 3 hours.

In this scenario, I wrote an efficient algorithm for capacity-limited passenger assignment. I then developped multiple destroy and repair operators, which I incorporated into the [`biogeme-optimization`](https://github.com/michelbierlaire/optimization) framework and tested on a simplified case study, based on the dutch network and with two objectives.

The heuristic demonstrated a capacity to find solutions near the pareto frontier in a reasonable time. Multiple insights on the operators efficiency were produced, making future iterations of the process posible.

This repo countains the final report of this project. The code is under a confidentiality agreement, and can therefore not be shared.
