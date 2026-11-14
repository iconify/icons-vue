<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xyx8_yu5p"/><path class="jfbs43d9j"/><path class="vzypl5bay"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:roi-metric" /></template>
<style>
.jfbs43d9j {
  d: path("M10 12.25q-.375-.75-1.5-.75c-1 0-1.5.5-1.5 1.25c0 1.5 3.25 1 3.25 2.75c0 .75-.75 1.25-1.75 1.25c-.75 0-1.5-.25-1.75-.75m1.75-5.75v1.25m0 5.25V18m3.75-9c1.75-4.5 8.25-6 9-1.25c.5 3.25-2.25 5.5-5 6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vzypl5bay {
  d: path("m18 11.75l-1.75 2l2.25 1.5");
}

.xyx8_yu5p {
  d: path("M2.5 14.5a6 6 0 1 0 12 0a6 6 0 1 0-12 0Z");
}

</style>
