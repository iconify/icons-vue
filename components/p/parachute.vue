<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g7pjsyb7t"/><rect class="il9qhfb8l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:parachute" /></template>
<style>
.g7pjsyb7t {
  d: path("M2.75 11.25a9.25 8.5 0 0 1 18.5 0c-1.5-1.25-3.1-1.25-4.6 0c-1.5-1.25-3.1-1.25-4.65 0c-1.5-1.25-3.1-1.25-4.6 0c-1.5-1.25-3.1-1.25-4.65 0m0 0l7.5 6.5m11-6.5l-7.5 6.5M12 11.25v6.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.il9qhfb8l {
  width: 4.5px;
  height: 3.5px;
  x: 9.75px;
  y: 17.75px;
  rx: 1px;
}

</style>
