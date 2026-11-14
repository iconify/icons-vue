<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rsudimb0g"/><path class="aywr_g0kk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sports-radio" /></template>
<style>
.aywr_g0kk {
  d: path("M14.5 16.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-8.5 0h5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rsudimb0g {
  d: path("M6 11.5h12a3.5 3.5 0 0 1 3.5 3.5v2.5A3.5 3.5 0 0 1 18 21H6a3.5 3.5 0 0 1-3.5-3.5V15A3.5 3.5 0 0 1 6 11.5m.75-5a7 7 0 0 1 10.5 0m-8 2a3.75 3.75 0 0 1 5.5 0");
}

</style>
