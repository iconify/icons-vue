<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ym_viizjx"/><path class="t8drptb8d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:on-the-record" /></template>
<style>
.t8drptb8d {
  d: path("M9.5 14.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm2.5-11v2.75M6 8.5L4.25 6.75M18 8.5l1.75-1.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ym_viizjx {
  d: path("M6.5 14.5a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Z");
}

</style>
