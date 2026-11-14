<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xdaccxj-b"/><path class="o462ftb6f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:measure-light" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o462ftb6f {
  d: path("M8 17a4 4 0 0 1 8 0m-4 0l2.75-2.75M12 2.5V6M6 4l1.25 2M18 4l-1.25 2");
}

.xdaccxj-b {
  d: path("M9.875 9h4.25a4.375 4.375 0 0 1 4.375 4.375v3.75a4.375 4.375 0 0 1-4.375 4.375h-4.25A4.375 4.375 0 0 1 5.5 17.125v-3.75A4.375 4.375 0 0 1 9.875 9");
}

</style>
