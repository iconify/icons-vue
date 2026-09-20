<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="lnl_x_tyf"/><path class="ftkg-wssi"/><path class="ly9z-9bhd"/><path class="i4zv2obgy"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mnst-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ftkg-wssi {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.615 16.779a6 6 0 0 1-1.58.58c.17-.59.26-1.215.26-1.86c0-3.59-2.8-6.5-6.25-6.5c-.44 0-.87.05-1.285.14c.77-2.69 3.16-4.64 5.99-4.64c3.45 0 6.25 2.91 6.25 6.5c0 1.62-.57 3.1-1.515 4.24a1.248 1.248 0 0 0-1.954.731a1.25 1.25 0 0 0 .084.803z");
}

.i4zv2obgy {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.25 9.499a1.75 1.75 0 1 0 0-3.5a1.75 1.75 0 0 0 0 3.5m-3.5-1a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5m6.75 2.499a1 1 0 1 0 0-2a1 1 0 0 0 0 2m-.5 2.501a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1m-4.045 5.4a4.58 4.58 0 0 0 2.13-3.88a4.523 4.523 0 0 0-4.48-4.56c-1.14 0-2.29.575-3.2 1.445c.48.3 1.085.715 1.3.93a3.22 3.22 0 0 0-2.75 2.54c.42-.095 1.36-.185 1.72.195c-.295.475-1.245 1.89-2.675 3.745c.84.25 2.925.285 4.56-1.625c.12.29.215 1.05-.36 1.765c.69.16 2.315 0 3.325-1.92c.075.31.23.88.43 1.37z");
}

.lnl_x_tyf {
  fill: var(--svg-color--a8d3d9, #a8d3d9);
  d: path("M24 0H0v24h24z");
}

.ly9z-9bhd {
  fill: var(--svg-color--fff, #fff);
  d: path("m17.88 6.124l-4.6 4.6a6.1 6.1 0 0 0-5.52-1.585c.77-2.69 3.16-4.64 5.99-4.64c1.585 0 3.03.615 4.13 1.625");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
