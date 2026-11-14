<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qsp5rjb-f"/><path class="goes4mb5x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:smartphone-wifi" /></template>
<style>
.goes4mb5x {
  d: path("M10.055 12.055a2.75 2.75 0 0 1 3.89 0m-5.657-1.767a5.25 5.25 0 0 1 7.424 0");
}

.qsp5rjb-f {
  d: path("M6 2.5h12v19H6ZM10.5 18h3M12 14h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
