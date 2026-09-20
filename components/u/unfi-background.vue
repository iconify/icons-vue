<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="zimlh4bqd"/><path class="cphy9mbgn"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:unfi-background" /></template>
<style>
.cphy9mbgn {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.215 4h5.45L20 7.336v5.45l-3.336 3.335h-5.45L7.88 12.785v-5.45zm.6 1.455L9.334 7.937v4.247l2.483 2.483h4.247l2.483-2.483V7.937l-2.483-2.482z");
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

.zimlh4bqd {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.336 7.879h5.45l3.335 3.336v5.45L12.785 20h-5.45L4 16.664v-5.45zm.6 1.454l-2.481 2.483v4.247l2.482 2.482h4.247l2.483-2.482v-4.247l-2.483-2.483z");
}

</style>
