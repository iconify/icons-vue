<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ek9n8bb0a"/><path class="oy3_m2blq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:shoplifting" /></template>
<style>
.ek9n8bb0a {
  fill: currentColor;
  d: path("M2.5 6C2.5 4.5 4 3.5 6 3.5h12c2 0 3.5 1 3.5 2.5v1.5c0 2.5-2 4-4.5 4s-3.5-2-5-2s-2.5 2-5 2s-4.5-1.5-4.5-4Zm2.25 1.25a2.25 1.5 0 0 0 4.5 0a2.25 1.5 0 0 0-4.5 0Zm10 0a2.25 1.5 0 0 0 4.5 0a2.25 1.5 0 0 0-4.5 0Z");
}

.oy3_m2blq {
  d: path("M14.5 15.5h7v6h-7Zm0 2.25h7M18 15.5v2.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
