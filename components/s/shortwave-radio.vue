<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rqlutefrv"/><path class="patdnnb-x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:shortwave-radio" /></template>
<style>
.patdnnb-x {
  d: path("M5.25 14.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm8.75 0h4.5");
}

.rqlutefrv {
  d: path("M2.5 8h19v13h-19ZM15 8l5-5.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
