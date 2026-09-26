<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="vl5-qwbrw"/><path class="rfs8_o06a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:test-tubes-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rfs8_o06a {
  d: path("M3 2L9 2L9 19C9 20.6569 7.6569 22 6 22C4.3431 22 3 20.6569 3 19L3 2ZM1 2L11 2M3 13L9 13M15 2L21 2L21 19C21 20.6569 19.6569 22 18 22C16.3431 22 15 20.6569 15 19L15 2ZM13 2L23 2M15 16L21 16");
}

.vl5-qwbrw {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 1L9 1C9.5523 1 10 1.4477 10 2L10 19C10 21.2091 8.2091 23 6 23C3.7909 23 2 21.2091 2 19L2 2C2 1.4477 2.4477 1 3 1ZM15 1L21 1C21.5523 1 22 1.4477 22 2L22 19C22 21.2091 20.2091 23 18 23C15.7909 23 14 21.2091 14 19L14 2C14 1.4477 14.4477 1 15 1Z");
  stroke: none;
}

</style>
