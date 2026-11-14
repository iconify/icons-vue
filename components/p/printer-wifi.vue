<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jkis-ccym"/><path class="w5uglqbug"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:printer-wifi" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jkis-ccym {
  d: path("M6.875 4h10.25A4.375 4.375 0 0 1 21.5 8.375v1.75a4.375 4.375 0 0 1-4.375 4.375H6.875A4.375 4.375 0 0 1 2.5 10.125v-1.75A4.375 4.375 0 0 1 6.875 4M6.5 14.5v5a1 1 0 0 0 1 1h9a1 1 0 0 0 1-1v-5m-8 3h5M12 11h.01");
}

.w5uglqbug {
  d: path("M10.586 9.586a2 2 0 0 1 2.828 0M9.172 8.172a4 4 0 0 1 5.656 0");
}

</style>
