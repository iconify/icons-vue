<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p8u760b4u"/><path class="zn09u-uqs"/><path class="r36fqqz7u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:repo-insights" /></template>
<style>
.p8u760b4u {
  d: path("M3.5 3v17.5H21");
}

.r36fqqz7u {
  d: path("M15.75 7.5h3.75v3.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zn09u-uqs {
  d: path("m7 15.5l4-4.5l3 2.5l5.5-6");
}

</style>
