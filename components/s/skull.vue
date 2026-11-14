<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n2liq85nr"/><path class="jaaj21bhn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:skull" /></template>
<style>
.jaaj21bhn {
  d: path("M8 11a1.25 1.25 0 1 0 2.5 0A1.25 1.25 0 1 0 8 11Zm5.5 0a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0ZM12 17v3.5");
}

.n2liq85nr {
  d: path("M5.5 11c0-4.5 3-7.5 6.5-7.5s6.5 3 6.5 7.5c0 2.5-1.25 3.75-2.5 4.5v3a2 2 0 0 1-2 2h-4a2 2 0 0 1-2-2v-3c-1.25-.75-2.5-2-2.5-4.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
