<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zxxy0ibcb"/><path class="im96wybbr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:price-tag-string" /></template>
<style>
.im96wybbr {
  d: path("M10.5 14.25C9.5 11 7.5 8 5 6.5S3.5 2 6 2.75c2 .5 2 3 .25 4.5m4.25 7h.01M14 12h4.5M14 16.5h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zxxy0ibcb {
  d: path("M11 7h10.5v14.5H11l-5-7.25Z");
}

</style>
