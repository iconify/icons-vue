<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vv0k9fbnm"/><path class="bxvoogjps"/><path class="uli3sd04w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:thermometer-cold" /></template>
<style>
.bxvoogjps {
  fill: currentColor;
  d: path("M5.5 16.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.uli3sd04w {
  d: path("M17.5 8.5v11M13.75 12l7.5 4m-7.5 0l7.5-4m-5.5-3.5l1.75 1.75l1.75-1.75m-3.5 11l1.75-1.75l1.75 1.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vv0k9fbnm {
  d: path("M5 13V5a2 2 0 0 1 4 0v8a3.75 3.75 0 1 1-4 0Z");
}

</style>
