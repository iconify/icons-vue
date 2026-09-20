<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="d4ng15vyg"/><path class="r_suce00m"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ply-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.d4ng15vyg {
  fill: var(--svg-color--8dd9f6, #8dd9f6);
  d: path("M13.5 18.488a6.5 6.5 0 1 0 0-13a6.5 6.5 0 0 0 0 13");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r_suce00m {
  fill: var(--svg-color--6161f6, #6161f6);
  d: path("M14.56 13.219a1.5 1.5 0 0 0-.013-2.565L6.272 5.692A1.5 1.5 0 0 0 4 6.98v10.04a1.5 1.5 0 0 0 2.285 1.28z");
}

</style>
