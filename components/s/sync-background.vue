<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGeUifmchS)" class="r4i437pya"/><path class="m1l_ddbqd"/></g><defs><linearGradient id="SVGeUifmchS" x1="14.893" x2="5.217" y1="5.857" y2="12.7" gradientUnits="userSpaceOnUse"><stop class="ua6d_t1fc"/><stop offset="1" class="u55h1-bby"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sync-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m1l_ddbqd {
  fill: var(--svg-color--fff, #fff);
  d: path("m15.65 7.135l.85-2.14C16 4.665 14.505 4 12.545 4c-2.45 0-4.53 1.4-4.53 3.5c-.03.757.239 1.496.75 2.055l-.035.035c-.425.415-1.23 1.205-1.23 2.53c0 1.365.81 2.525 3.42 3.1c2.08.48 2.58.885 2.58 1.415s-.855 1.1-1.985 1.1c-1.125 0-2.57-.67-3.105-1.1L7.5 18.86c.55.38 2.13 1.14 4.015 1.14c2.35 0 4.47-1.1 4.47-3.56a3.25 3.25 0 0 0-.83-2.04a3.25 3.25 0 0 0 1.345-2.565c0-1.77-1.7-2.685-3.64-3.135s-2.36-.81-2.36-1.38s.78-1.04 2.045-1.04s2.25.35 3.1.855zM10.97 10.5l1.7.455c.45.115 1.33.525 1.33 1.22s-.635 1.175-.95 1.325l-1.59-.39c-.49-.16-1.46-.635-1.46-1.26c0-.63.65-1.16.97-1.35");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.u55h1-bby {
  stop-color: var(--svg-color--4f69d4, #4f69d4);
}

.ua6d_t1fc {
  stop-color: var(--svg-color--2abecd, #2abecd);
}

</style>
