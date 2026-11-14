<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vgt2cab1q"/><path class="j6xa6doeg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:overhead-crane" /></template>
<style>
.j6xa6doeg {
  d: path("M9.5 4h5v3h-5ZM12 7v2.5M9.5 12L12 9.5l2.5 2.5m-6 0h7v6.5h-7Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vgt2cab1q {
  d: path("M3 21.5V4h18v17.5");
}

</style>
