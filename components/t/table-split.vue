<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="udgrlbscn"/><path class="anwf4h-1y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:table-split" /></template>
<style>
.anwf4h-1y {
  d: path("M9.25 15H5.5m2-2l-2 2l2 2m7.25-2h3.75m-2-2l2 2l-2 2");
}

.udgrlbscn {
  d: path("M2.5 3.5h19v17h-19Zm0 5.5h19M12 9v11.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
