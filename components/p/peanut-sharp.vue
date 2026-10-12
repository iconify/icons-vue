<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="wtn86yjtl"/><path class="h06bnrbuh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:peanut-sharp" /></template>
<style>
.h06bnrbuh {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.75 6.5h.01m2.49 2.25h.01m-3.01 7.5h.01m3.49 1.5h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.wtn86yjtl {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75c2.5 0 4.5 2 4.5 4.5v1.677l-1.25 1.923l-.555.872l.655.728c1.2 1.2 2.4 2.5 2.4 4.55c0 2.4-2.5 4.25-5.75 4.25S6.25 19.4 6.25 17c0-2.05 1.2-3.35 2.4-4.55l.655-.728l-.555-.872L7.5 8.927V7.25c0-2.5 2-4.5 4.5-4.5Z");
}

</style>
