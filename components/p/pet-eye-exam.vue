<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aed7vxbmr"/><path class="tm3bv4e7e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pet-eye-exam" /></template>
<style>
.aed7vxbmr {
  d: path("M12.571 14.482Q7.536 14.801 2.5 9.5q9.5-10 19 0q-1.559 1.641-3.118 2.744");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tm3bv4e7e {
  d: path("M9.5 9.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m6 10.5a2.5 1.5 0 1 0 5 0a2.5 1.5 0 1 0-5 0m-.75-3.75h.01M18 15h.01m3.24 1.25h.01");
}

</style>
