<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x9_mdgbcg"/><path class="d6yxgcb0a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:map-layer-ev-chargers" /></template>
<style>
.d6yxgcb0a {
  d: path("M10.75 6.5L7.5 12H11l-2.25 5.5M14.5 14h3a2 2 0 0 0 2-2V6L18 4.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x9_mdgbcg {
  d: path("M4 3h10.5v18H4Z");
}

</style>
