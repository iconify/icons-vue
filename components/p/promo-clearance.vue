<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nf99v2b4s"/><path class="v6_g-8bua"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:promo-clearance" /></template>
<style>
.nf99v2b4s {
  d: path("M2.5 2.5H9l7.5 7.5l-6.5 6.5L2.5 9Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v6_g-8bua {
  d: path("M5 6.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm13 8v7m-3-3l3 3l3-3");
}

</style>
