<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="v130o4r9t"/><path class="w1s6e9bah"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mobile-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.v130o4r9t {
  fill: var(--svg-color--009ff9, #009ff9);
  d: path("M24 0H0v24h24z");
}

.w1s6e9bah {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 7.195a1.333 1.333 0 0 1 2.667 0v9.61a1.334 1.334 0 1 1-2.667 0zm13.333 0a1.334 1.334 0 0 1 2.667 0v9.61a1.334 1.334 0 0 1-2.667 0zM8.533 9.6A1.34 1.34 0 0 0 7.2 10.95v5.834c0 .747.597 1.35 1.333 1.35a1.34 1.34 0 0 0 1.334-1.35v-5.835A1.34 1.34 0 0 0 8.533 9.6m5.6 1.35c0-.747.598-1.35 1.334-1.35a1.34 1.34 0 0 1 1.333 1.35v5.834a1.34 1.34 0 0 1-1.333 1.35a1.34 1.34 0 0 1-1.334-1.35zM12 13.36a1.333 1.333 0 0 0-1.333 1.328v2.117a1.334 1.334 0 0 0 2.666 0v-2.117A1.333 1.333 0 0 0 12 13.355z");
}

</style>
