<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d1bppzjxc"/><path class="gl27z_kck"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:security-camera-eye" /></template>
<style>
.d1bppzjxc {
  d: path("m5.172 8.968l6.578-2.394a3.5 3.5 0 0 1 4.486 2.092l.684 1.88a3.5 3.5 0 0 1-2.092 4.486L8.25 17.426a3.5 3.5 0 0 1-4.486-2.092l-.684-1.88a3.5 3.5 0 0 1 2.092-4.486M16.5 9.5h5m0-4v8");
}

.gl27z_kck {
  d: path("M6 12a3.5 1.75 0 1 0 7 0a3.5 1.75 0 1 0-7 0m3.5.25h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
