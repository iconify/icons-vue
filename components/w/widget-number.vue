<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nirj1m4jo"/><path class="qy27zcbtl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:widget-number" /></template>
<style>
.nirj1m4jo {
  d: path("M2.5 2.5h19v19h-19Zm0 6h19M10 4.5h.01m1.99 0h.01m1.99 0h.01M10 6.5h.01m1.99 0h.01m1.99 0h.01");
}

.qy27zcbtl {
  d: path("m6.25 13.75l1.5-1.5v6m2.25-4.5a1.5 1.5 0 0 1 3 0c0 2-3 2.75-3 4.5h3m2.25-6h2.5L16.25 15A1.75 1.75 0 1 1 15 17.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
