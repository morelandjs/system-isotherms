# Collision system isotherms

Isotherms at T=100, 155 and 200 MeV for Pb-Pb, p-Pb and p-p collisions at 5.02 TeV

## Regenerating figures

The prediction figures are stored in the git repo plots folder for convenience, but they can easily be regenerated.

First, follow the [installation instructions](https://github.com/morelandjs/hic-eventgen/tree/isotherm/local) to install the `isotherm` branch of [hic-eventgen](https://github.com/morelandjs/hic-eventgen).

Then clone and cd into the system-isotherms project repository,
```
git clone https://github.com/morelandjs/system-isotherms.git && cd system-isotherms
```
Make sure the hic-eventgen `run-events` executable is in your path and `$XDG_DATA_HOME` is sourced as explained in the hic-eventgen installation instructions.

Finally run,
```
python make-plots
```
to regenerate the figures. This could take some time.

## Figure descriptions

The following documentation describes each of the figures in the `plots` directory.

### Multiplicity distribution
![alt text](https://github.com/morelandjs/system-isotherms/plots/mult_dist.png)

### Single-shot events
![alt text](https://github.com/morelandjs/system-isotherms/plots/single_shot_events.png)

### Isotherms
![alt text](https://github.com/morelandjs/system-isotherms/plots/isotherms.png)
