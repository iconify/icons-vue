<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p1m3b6bcp"/><path class="z2foromno"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:open-source-licence" /></template>
<style>
.p1m3b6bcp {
  d: path("M11.7 21H3V2.5h14v7.6M6.5 7h7m-7 4h7m-7 4H10m4.5 1.5h7v5h-7Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z2foromno {
  d: path("M16.25 16.5v-2a1.75 1.75 0 0 1 3.5 0");
}

</style>
