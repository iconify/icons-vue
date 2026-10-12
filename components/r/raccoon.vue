<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="peueqrb8f"/><path class="je_2xl-5q"/><path class="bj36zojuv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:raccoon" /></template>
<style>
.bj36zojuv {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.25 12h.01m5.49 0h.01M12 16.5h.01");
}

.je_2xl-5q {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 11.25c1.5-.75 3.5-1.1 5-.25c1.5-.85 3.5-.5 5 .25c0 1.4-1 2.25-2.25 2.25c-1.1 0-2-.5-2.75-1.1c-.75.6-1.65 1.1-2.75 1.1C8 13.5 7 12.65 7 11.25");
}

.peueqrb8f {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 4.5c.25-.75 1-1 1.75-.5L10 6h4l2.75-2c.75-.5 1.5-.25 1.75.5l1 4.5c1 2 1.25 4 .5 5.5L13.5 20c-.75.75-2.25.75-3 0L4 14.5C3.25 13 3.5 11 4.5 9Z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
