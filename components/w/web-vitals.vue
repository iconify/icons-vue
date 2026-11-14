<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nnbtrjb1j"/><path class="vr-402b1a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:web-vitals" /></template>
<style>
.nnbtrjb1j {
  d: path("M2.5 4h19v16h-19Zm0 4.5h19m-16-2.25h.01m2.74 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vr-402b1a {
  d: path("M2.5 14.5H7l2-3.25L11.5 18l2.25-5.5l1.5 2h6.25");
}

</style>
