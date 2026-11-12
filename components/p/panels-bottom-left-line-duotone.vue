<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="sc-ztr_yu"/><path class="q2b-y-cmq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panels-bottom-left-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q2b-y-cmq {
  d: path("M22 14.5001L2 14.5001M9 2.02014L9 14.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.sc-ztr_yu {
  d: path("M2 12C2 16.714 2 19.0711 3.46447 20.5355C4.92893 22 7.28595 22 12 22C16.714 22 19.0711 22 20.5355 20.5355C22 19.0711 22 16.714 22 12C22 7.28595 22 4.92893 20.5355 3.46446C19.0711 2 16.714 2 12 2C7.28595 2 4.92893 2 3.46446 3.46447C2 4.92893 2 7.28595 2 12Z");
}

</style>
