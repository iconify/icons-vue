<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u4pxavdfk"/><path class="vy9ix2iwf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:video-channel" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u4pxavdfk {
  d: path("M6.875 9.5h10.25a4.375 4.375 0 0 1 4.375 4.375v3.25a4.375 4.375 0 0 1-4.375 4.375H6.875A4.375 4.375 0 0 1 2.5 17.125v-3.25A4.375 4.375 0 0 1 6.875 9.5");
}

.vy9ix2iwf {
  d: path("m12.29 13.667l.9.558a1.5 1.5 0 0 1 0 2.55l-.9.558A1.5 1.5 0 0 1 10 16.057v-1.114a1.5 1.5 0 0 1 2.29-1.276M9 6.75a4.25 4.25 0 0 1 6 0M5.5 5a9 9 0 0 1 13 0");
}

</style>
