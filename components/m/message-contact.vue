<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bdi4m5fsu"/><path class="re6xhdcnc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:message-contact" /></template>
<style>
.bdi4m5fsu {
  d: path("M5 3h13.5A2.5 2.5 0 0 1 21 5.5v10a2.5 2.5 0 0 1-2.5 2.5H8.75l-4 3v-3H5a2.5 2.5 0 0 1-2.5-2.5v-10A2.5 2.5 0 0 1 5 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.re6xhdcnc {
  d: path("M10.5 8A2.25 2.25 0 1 0 15 8a2.25 2.25 0 1 0-4.5 0M8.75 18c0-3 1.75-5 4-5s4 2 4 5");
}

</style>
