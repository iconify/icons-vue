<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qcsa44b0h"/><path class="znvx79hss"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-racetrack" /></template>
<style>
.qcsa44b0h {
  d: path("M4.5 2.5v19m0-18h15v10h-15Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.znvx79hss {
  fill: currentColor;
  d: path("M4.5 3.5h5v5h-5Zm10 0h5v5h-5Zm-5 5h5v5h-5Z");
}

</style>
