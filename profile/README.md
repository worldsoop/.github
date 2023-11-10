## Building more realistic environments for machine learning systems

Welcome to the [WorldsOOp software ecosystem](https://github.com/orgs/worldsoop/)!. Our goal here is to create more realistic environments for machine learning systems to train on and test themselves against.

_State observation is not easy._

These challenging environments have been designed reflect the difficulties with handling more realistic datasets, as well as the partial state observability that is nearly always the case when working on problems in the real world.

_Gamified realism for machine learning._

Access to real data for the systems that matter is often restricted. We want to circumvent this barrier to generalisation research into practical ML systems by generating it from environments instead. Nothing replaces a real dataset; but we can always try to emulate how messy it gets while still knowing the ground truth!

## Environments

[![ReadMe Card](https://github-readme-stats.vercel.app/api/pin/?username=worldsoop&repo=trywizard)](https://github.com/worldsoop/trywizard)
[![ReadMe Card](https://github-readme-stats.vercel.app/api/pin/?username=worldsoop&repo=paraspace)](https://github.com/worldsoop/paraspace)
[![ReadMe Card](https://github-readme-stats.vercel.app/api/pin/?username=worldsoop&repo=market-envy)](https://github.com/worldsoop/market-envy)
[![ReadMe Card](https://github-readme-stats.vercel.app/api/pin/?username=worldsoop&repo=relief-chains)](https://github.com/worldsoop/relief-chains)
[![ReadMe Card](https://github-readme-stats.vercel.app/api/pin/?username=worldsoop&repo=anglersim)](https://github.com/worldsoop/anglersim)

## Software foundations

The fundamental software foundations for all of our environments originate from the designs laid out in this open source book: [Worlds Of Observation](https://umbralcalc.github.io/worlds-of-observation/).

- The [stochadex](https://github.com/umbralcalc/stochadex) is a fully generalised, highly configurable, stochastic simulation framework written with a concurrent backend architecture and a frontend dashboard for visualisation. You can read the [GoDocs here](https://pkg.go.dev/github.com/umbralcalc/stochadex).
- The [learnadex](https://github.com/umbralcalc/learnadex) is a concurrent, generalised, online learning and MAP inference framework which accompanies a RESTful API to query the results from. There's also a dashboard app for viewing API queries. You can read the [GoDocs here](https://pkg.go.dev/github.com/umbralcalc/learnadex).

