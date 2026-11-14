<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bfal9xbpv"/><path class="iin86stce"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:traffic-map" /></template>
<style>
.bfal9xbpv {
  d: path("m12.733 20.383l-.233.117l-5-2.5l-5 2.5V6l5-2.5l5 2.5l5-2.5v2.729M7.5 3.5V18m5-12v14.5");
}

.iin86stce {
  d: path("M16.5 9h4a1 1 0 0 1 1 1v10.5a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1V10a1 1 0 0 1 1-1Zm2 3h.01m-.01 3.25h.01m-.01 3.25h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
