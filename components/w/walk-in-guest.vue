<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dye7ntbqy"/><path class="y_35z-buh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:walk-in-guest" /></template>
<style>
.dye7ntbqy {
  d: path("M9.5 4a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm1 3.5l-2 6l3 3V21m-3-7.5l-2 4l-2.5 3m12.5.5V3.5h5V21");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y_35z-buh {
  d: path("m5.5 11l4-3l4 3.5");
}

</style>
