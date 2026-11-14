<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mv--q0bhl"/><path class="wx7bfu3zy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pedestrian-walkway" /></template>
<style>
.mv--q0bhl {
  d: path("M11.25 4.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm1.75 5L11.5 14L8 18.25M11.5 14l2.75 1.75l.5 2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wx7bfu3zy {
  d: path("m8.5 12.5l4.25-2.5l3.75 2M3 21h3.5m3.75 0h3.5m3.75 0H21");
}

</style>
