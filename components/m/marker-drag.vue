<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ez1radbqn"/><path class="frj3jmozf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:marker-drag" /></template>
<style>
.ez1radbqn {
  d: path("M12 14.75C10.25 13 6.5 10.75 6.5 8a5.5 5.5 0 0 1 11 0c0 2.75-3.75 5-5.5 6.75");
}

.frj3jmozf {
  d: path("M10 8a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-.75 11h5.5m-9-2.25L3.5 19l2.25 2.25m12.5-4.5L20.5 19l-2.25 2.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
