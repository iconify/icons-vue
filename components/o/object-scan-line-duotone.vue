<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="i8utatbio"/><path class="vepd3ytoq"/><path class="un-u7xpwr"/><path class="qpmqs1x2s"/><path class="lg_7281ce"/><path class="i-375ubnr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:object-scan-line-duotone" /></template>
<style>
.i-375ubnr {
  d: path("M18 10V9.5C18 7.61438 18 6.67157 17.4142 6.08579C16.8284 5.5 15.8856 5.5 14 5.5H10C8.11438 5.5 7.17157 5.5 6.58579 6.08579C6 6.67157 6 7.61438 6 9.5V14.5C6 16.3856 6 17.3284 6.58579 17.9142C7.17157 18.5 8.11438 18.5 10 18.5H14C15.8856 18.5 16.8284 18.5 17.4142 17.9142C18 17.3284 18 16.3856 18 14.5V10.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.i8utatbio {
  d: path("M22 14C22 17.7712 22 19.6569 20.8284 20.8284C19.6569 22 17.7712 22 14 22");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lg_7281ce {
  d: path("M4 11.5C4 11.5 6.4 9.5 12 9.5C17.6 9.5 20 11.5 20 11.5");
}

.qpmqs1x2s {
  d: path("M14 2C17.7712 2 19.6569 2 20.8284 3.17157C22 4.34315 22 6.22876 22 10");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.un-u7xpwr {
  d: path("M10 2C6.22876 2 4.34315 2 3.17157 3.17157C2 4.34315 2 6.22876 2 10");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.vepd3ytoq {
  d: path("M10 22C6.22876 22 4.34315 22 3.17157 20.8284C2 19.6569 2 17.7712 2 14");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
