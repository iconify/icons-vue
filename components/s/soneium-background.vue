<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="z1iik-bpq"/><path class="du_bc-bbb"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:soneium-background" /></template>
<style>
.du_bc-bbb {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.968 7.677a4.43 4.43 0 0 1 4.168 1.174c1.462 1.463 1.747 3.635.692 5.352a7.6 7.6 0 0 1-1.208 1.494a2502 2502 0 0 1-4.184 4.147a8 8 0 0 0 5.846-1.085a8.01 8.01 0 0 0 2.67-10.722a8 8 0 0 0-4.65-3.708z");
}

.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.z1iik-bpq {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.025 16.327a4.43 4.43 0 0 1-4.169-1.175a4.306 4.306 0 0 1-.697-5.36A7.5 7.5 0 0 1 9.367 8.3c1.475-1.471 4.184-4.148 4.184-4.148a8 8 0 0 0-5.838 1.092a8.01 8.01 0 0 0-2.67 10.71a8 8 0 0 0 4.64 3.711z");
}

</style>
