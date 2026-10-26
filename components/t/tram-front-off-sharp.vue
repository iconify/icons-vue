<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="sascdph9u"/><path class="i88y1sd6n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tram-front-off-sharp" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.i88y1sd6n {
  fill: currentColor;
  d: path("M9 16C9 16.5523 8.5523 17 8 17C7.4477 17 7 16.5523 7 16C7 15.4477 7.4477 15 8 15C8.5523 15 9 15.4477 9 16Z");
  stroke: none;
}

.sascdph9u {
  d: path("M20 20L4 20L4 6L6 6M4 12L12 12M8 20L6.7236 22.5528M16 20L17.2764 22.5528M10.6569 6L20 6L20 15.3431M16.6569 12L20 12M7 2L17 2M10.5314 4.9372L12 2L14 6M1.7071 1.7071L22.2929 22.2929");
}

</style>
