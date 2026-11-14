<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hcauwkbvm"/><path class="ighr8abuq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ski-tracks" /></template>
<style>
.hcauwkbvm {
  d: path("M6 21.5c0-5.5 6.5-7 6.5-12.5c0-3-1.5-5-3.5-6.5");
}

.ighr8abuq {
  d: path("M10 21.5c0-5.5 6.5-7 6.5-12.5c0-3-1.5-5-3.5-6.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
