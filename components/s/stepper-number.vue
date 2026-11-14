<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="linob4bwz"/><path class="m8i79gbtl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:stepper-number" /></template>
<style>
.linob4bwz {
  d: path("M2.5 6.5h19v11h-19Zm5.5 0v11m8-11v11M4 12h2.5m11 0H20m-1.25-1.25v2.5");
}

.m8i79gbtl {
  d: path("m11 10l1.25-1v6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
