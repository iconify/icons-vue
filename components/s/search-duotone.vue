<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="venhj685r"/><path class="xexl16bfr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:search-duotone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.venhj685r {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 2C14.4184 2 18 5.5816 18 10C18 14.4184 14.4184 18 10 18C5.5816 18 2 14.4184 2 10C2 5.5816 5.5816 2 10 2Z");
  stroke: none;
}

.xexl16bfr {
  d: path("M15 15L21 21");
}

</style>
