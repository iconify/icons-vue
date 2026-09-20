<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="lov2r0bmi"/><path class="ryus0bcfz"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:multiversx-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lov2r0bmi {
  fill: var(--svg-color--23f7dd, #23f7dd);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.ryus0bcfz {
  fill: var(--svg-color--000, #000);
  d: path("m13 12l7-3.748L18.798 6l-6.537 2.45a.7.7 0 0 1-.523 0L5.202 6L4 8.26L11 12l-7 3.74L5.202 18l6.536-2.45a.7.7 0 0 1 .523 0L18.798 18L20 15.728z");
}

</style>
