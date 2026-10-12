<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="drbi0rnnl"/><path class="rjtfrzb-f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rotate-square-ccw" /></template>
<style>
.drbi0rnnl {
  d: path("M3.75 12a8.25 8.25 0 1 0 2.42-5.83L3.75 8.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rjtfrzb-f {
  d: path("M3.75 3.75v4.5h4.5");
}

</style>
