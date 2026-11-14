<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ufa9yivum"/><path class="p_taqacgq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:outdoor-kitchen" /></template>
<style>
.p_taqacgq {
  d: path("M15 9.25V3.5h3v8M2.5 17h19M5 17v4.5M19 17v4.5M8.5 17v-2.5a3.5 3.5 0 0 1 7 0V17");
}

.ufa9yivum {
  d: path("M4 17a8 8.5 0 0 1 16 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
