<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cl5je1bxq"/><path class="y8p9kxxre"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:printing-plate" /></template>
<style>
.cl5je1bxq {
  d: path("M6.125 4h9.788a2.63 2.63 0 0 1 1.856.769l1.962 1.962a2.63 2.63 0 0 1 .769 1.856v8.788A2.625 2.625 0 0 1 17.875 20H6.125A2.625 2.625 0 0 1 3.5 17.375V6.625A2.625 2.625 0 0 1 6.125 4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y8p9kxxre {
  d: path("M14.5 16.5v-9h-3a2.25 2.25 0 0 0 0 4.5h3M12 12l-2.5 4.5m-3-4.5h.01m11.24 0h.01");
}

</style>
