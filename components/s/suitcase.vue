<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="gg_xxm92g"/><path class="g4z0ns74a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:suitcase" /></template>
<style>
.g4z0ns74a {
  d: path("M9 7.25v-1.5a1.5 1.5 0 0 1 1.5-1.5h3a1.5 1.5 0 0 1 1.5 1.5v1.5m-7.75 0v13.5m9.5-13.5v13.5");
}

.gg_xxm92g {
  width: 18.5px;
  height: 13.5px;
  x: 2.75px;
  y: 7.25px;
  rx: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
