<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="c6mzz1jyl"/><path class="baj129bmc"/><path class="thu-4nvfu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ouroboros" /></template>
<style>
.baj129bmc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 2.75h2.75q1 0 1.73.68l1.79 1.64q.73.68 0 1.36l-1.79 1.64q-.73.68-1.73.68H9.5q-1 0-1-1v-4q0-1 1-1");
}

.c6mzz1jyl {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16 5.82a8 8 0 1 1-8 0l1.25 2.17a5.5 5.5 0 1 0 5.5 0Z");
}

.thu-4nvfu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.25 5.75h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
