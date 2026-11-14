<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ju2ll-m2d"/><path class="rv4w--jmr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:welcome-kit" /></template>
<style>
.ju2ll-m2d {
  d: path("M3.5 8h17L19 21.5H5ZM6 8V5a2.25 2.25 0 0 1 4.5 0v3m3 0V5A2.25 2.25 0 0 1 18 5v3");
}

.rv4w--jmr {
  d: path("M12 18.5c-1.75-1.25-3.25-2.5-3.25-4.25C8.75 13 9.75 12 11 12c.5 0 .75.25 1 .75c.25-.5.5-.75 1-.75c1.25 0 2.25 1 2.25 2.25c0 1.75-1.5 3-3.25 4.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
