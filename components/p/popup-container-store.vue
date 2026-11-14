<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t5aw-obyt"/><path class="lkx54rb1l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:popup-container-store" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lkx54rb1l {
  d: path("M15.25 8.5h2a1.5 1.5 0 0 1 1.5 1.5v7.5a1.5 1.5 0 0 1-1.5 1.5h-2a1.5 1.5 0 0 1-1.5-1.5V10a1.5 1.5 0 0 1 1.5-1.5M2.5 21.5h19");
}

.t5aw-obyt {
  d: path("M4.25 5.5h15.5a1.75 1.75 0 0 1 1.75 1.75v10A1.75 1.75 0 0 1 19.75 19H4.25a1.75 1.75 0 0 1-1.75-1.75v-10A1.75 1.75 0 0 1 4.25 5.5M5.5 8v8.5M8.25 8v8.5M11 8v8.5");
}

</style>
