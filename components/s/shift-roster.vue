<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hk6v1ml_g"/><path class="amlt10b0s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shift-roster" /></template>
<style>
.amlt10b0s {
  fill: currentColor;
  d: path("M7 11.75h3.5A1.25 1.25 0 0 1 11.75 13a1.25 1.25 0 0 1-1.25 1.25H7A1.25 1.25 0 0 1 5.75 13A1.25 1.25 0 0 1 7 11.75m5.25 4.5H17a1.25 1.25 0 0 1 1.25 1.25A1.25 1.25 0 0 1 17 18.75h-4.75A1.25 1.25 0 0 1 11 17.5a1.25 1.25 0 0 1 1.25-1.25");
}

.hk6v1ml_g {
  d: path("M6.5 4.5h11A3.5 3.5 0 0 1 21 8v10a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 18V8a3.5 3.5 0 0 1 3.5-3.5M3 9h18M8 2.5V6m8-3.5V6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
