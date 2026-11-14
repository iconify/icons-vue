<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pgt4riblf"/><path class="c8s-e-b8b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:throw-action" /></template>
<style>
.c8s-e-b8b {
  d: path("m14.25 14.75l4-2a1.5 1.5 0 0 1 1.5 2.5L14 19.5H2.5m10-14a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm-7 3l4-2");
}

.pgt4riblf {
  d: path("M2.5 13.5h3c1.5 0 2.75-1 4.5-1h3a1.5 1.5 0 0 1 0 3h-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
