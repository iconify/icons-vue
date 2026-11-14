<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wsr5fgb5v"/><path class="umwujrb5g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:page-number" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.umwujrb5g {
  d: path("M14.5 2.5v5h5M8 9.5h3.5m2 4.75l2-1.5v6");
}

.wsr5fgb5v {
  d: path("M4.5 2.5h10l5 5v14h-15Z");
}

</style>
