<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ohz9gnbrq"/><path class="tgysojb3e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:recipe-to-cart" /></template>
<style>
.ohz9gnbrq {
  d: path("M11.4 17H3V3h16v9.9M6.5 7.5h9m-9 4h6");
}

.tgysojb3e {
  d: path("M14.25 14.5h1.5l1 4.5h3.75l1.25-3.25H16m1.25 5.75h.01m2.99 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
