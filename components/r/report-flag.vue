<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="esfanjssi"/><path class="to8m3ibcr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:report-flag" /></template>
<style>
.esfanjssi {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 4.25c4.75-2 8.75 2 14.5 0a.75.75 0 0 1 1 .7v8.85a.75.75 0 0 1-.5.7c-5.75 2-9.75-2-15 0Zm0 17v-17m7.25 2V9.5");
}

.to8m3ibcr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
