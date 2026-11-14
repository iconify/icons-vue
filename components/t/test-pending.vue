<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v9fsaqbbk"/><path class="ifwt6hb9d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:test-pending" /></template>
<style>
.ifwt6hb9d {
  fill: currentColor;
  d: path("M16.5 21.25h3L18 19.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v9fsaqbbk {
  d: path("M6.5 3v11c0 2 1.5 3.5 3.5 3.5c.86 0 1.627-.277 2.223-.752M13.5 11.47V3M5 3h10m-8.5 7h7m1.5 4.25h6m-6 7.5h6m-5.25-7.5l4.5 7.5m0-7.5l-4.5 7.5");
}

</style>
