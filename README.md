# Datalust Helm charts

[Helm is a package manager for Kubernetes](https://helm.sh/). This repository contains the officially supported Helm chart
for [Seq](https://datalust.co/seq), a search and analysis server for structured application logs.

**For details of how to get started with Seq in Kubernetes, check out [the documentation](https://docs.datalust.co/docs/using-helm).**

:bulb: The chart's release process replaces `__VERSION__` in `Chart.yaml` with a specific Seq version number;
you'll need to edit this manually if you use the files from this repository as a basis for a customized chart.

## Acknowledgements

This chart was originally published [in the Helm v1 repository](https://github.com/helm/charts/tree/master/stable/seq), with contributions from @adamchester, @cpanato, @emmekappa, @gertjvr, @ggmaresca, @jonstelly, @KodrAus and @msschl :star_struck:.
