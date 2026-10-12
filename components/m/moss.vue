<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="d16f0q1nt"/><path class="e5piu6b3i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:moss" /></template>
<style>
.d16f0q1nt {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 20.25c0-2.75 2.75-4.75 6-4.75h6.5c3.25 0 6 2 6 4.75a1 1 0 0 1-1 1H3.75a1 1 0 0 1-1-1M7.5 15.5v-4c0-.75-.5-1.25-1.25-1.5M12 15.5V7c0-.75.5-1.25 1.25-1.5m3.25 10V10c0-.75.5-1.25 1.25-1.5");
}

.e5piu6b3i {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.25 10h.01m6.99-4.5h.01m4.49 3h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
