<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jwc02jhmg"/><path class="s1yv7xbwz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:panorama" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jwc02jhmg {
  d: path("M2.75 8.25a1 1 0 0 1 1.3-.95q7.95 2.4 15.9 0a1 1 0 0 1 1.3.95v7.5a1 1 0 0 1-1.3.95q-7.95-2.4-15.9 0a1 1 0 0 1-1.3-.95Z");
}

.s1yv7xbwz {
  d: path("m7 14.5l3-3l2.25 2.25L14 12l2.75 2.75");
}

</style>
