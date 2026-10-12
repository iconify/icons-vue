<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vk0qikjba"/><circle class="drtvz1btn"/><path class="ygyw9ob-w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:portrait-mode" /></template>
<style>
.drtvz1btn {
  cx: 12px;
  cy: 8.5px;
  r: 2.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vk0qikjba {
  d: path("M4.75 8V5.25a1.5 1.5 0 0 1 1.5-1.5H9m6 0h2.75a1.5 1.5 0 0 1 1.5 1.5V8m0 8v2.75a1.5 1.5 0 0 1-1.5 1.5H15m-6 0H6.25a1.5 1.5 0 0 1-1.5-1.5V16");
}

.ygyw9ob-w {
  d: path("M7.75 17.5a4.25 4.25 0 0 1 8.5 0Z");
}

</style>
