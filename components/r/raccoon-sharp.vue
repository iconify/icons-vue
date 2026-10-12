<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="yh4gd98ne"/><path class="ubgjx4j-s"/><path class="bj36zojuv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:raccoon-sharp" /></template>
<style>
.bj36zojuv {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.25 12h.01m5.49 0h.01M12 16.5h.01");
}

.ubgjx4j-s {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 11.25c1.5-.75 3.5-1.1 5-.25c1.5-.85 3.5-.5 5 .25v2.25h-3.625L12 12.4l-1.375 1.1H7z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.yh4gd98ne {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.5 4.5l.455-1.364L7.25 4L10 6h4l2.75-2l1.295-.864L18.5 4.5l1 4.5l1.625 3.25L20 14.5L13.5 20L12 21.5L10.5 20L4 14.5l-1.125-2.25L4.5 9Z");
}

</style>
