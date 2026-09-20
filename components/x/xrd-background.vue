<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="q0nj1tbdr"/><path class="b9_f2y6tv"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xrd-background" /></template>
<style>
.b9_f2y6tv {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 12.944V11.06h2.466c.226 0 .438.099.57.282l2.818 3.991l4.31-9.506a.71.71 0 0 1 .64-.414H20v1.882h-4.447l-4.927 11.012a.47.47 0 0 1-.81.085l-3.755-5.45z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q0nj1tbdr {
  fill: var(--svg-color--3ccf8d, #3ccf8d);
  d: path("M24 0H0v24h24z");
}

</style>
