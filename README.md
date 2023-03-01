# Sparkbadge 


Sparkbadges is a tool for create longitudinal status sparklines for your projects. For example:

![trend](examples/trend.svg)
![hist_trend](examples/hist_trend.svg)

The sparkline SVGs you create can then be implemented in a badge using a tool such as [google/pybadges](https://github.com/google/pybadges):

![commits](examples/commits.svg)
![build_time](examples/build_time.svg)

Sparkbadges was heavily influenced and inspired by [google/pybadges](https://github.com/google/pybadges) and the aesthetics of the [Shields.io](https://github.com/badges/shields) project.

## Usage

```
usage: sparkbadge [-h] [-o OWNER] [-r REPO]
                  [-s {histogram,bargraph,scatterplot}]
                  [-m {loc,coverage,deps,commits,issues,pr,wf_runs}] [-d DIR]

Generate sparklines for your status badge.

options:
  -h, --help            show this help message and exit
  -o OWNER, --owner OWNER
                        The repository owner.
  -r REPO, --repo REPO  The repository.
  -s {histogram,bargraph,scatterplot}, --sparkline {histogram,bargraph,scatterplot}
                        The sparkline to use.
  -m {loc,coverage,deps,commits,issues,pr,wf_runs}, --metrics {loc,coverage,deps,commits,issues,pr,wf_runs}
                        The metrics to create.
  -d DIR, --dir DIR     The directory to store sparkbadges. Default is
                        .sparkbadge/
```


## Development Roadmap

Check out the [project outline](docs/outline.md) to learn more.
