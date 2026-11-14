<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w-41v-p_t"/><path class="lg1onrblg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pet-ambulance" /></template>
<style>
.lg1onrblg {
  d: path("M5 19a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-7.75-6.5a1.75 1.5 0 1 0 3.5 0a1.75 1.5 0 1 0-3.5 0Zm-.5-3.75h.01M9 8.25h.01m2.24.5h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w-41v-p_t {
  d: path("M2.5 17V7A1.5 1.5 0 0 1 4 5.5h11l6.5 6V17Zm5-14H11v2.5H7.5Z");
}

</style>
