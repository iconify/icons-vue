<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pcm_l3n4g"/><path class="s-en5xboh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:trophy-chequered" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pcm_l3n4g {
  d: path("M5.5 3h10v4.5a5 5 0 0 1-10 0Z");
}

.s-en5xboh {
  d: path("M5.5 5H3v1.5A3.5 3.5 0 0 0 6.25 10m9.25-5H18v1.5a3.5 3.5 0 0 1-3.25 3.5m-4.25 2.5V17m2.9 3H7.5v-3h5.9m2.85 4.5V14h5.25v4.5h-5.25");
}

</style>
