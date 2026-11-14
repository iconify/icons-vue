<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i-pa0eb3g"/><path class="g923-ufzg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:training-workshop" /></template>
<style>
.g923-ufzg {
  d: path("m5.5 11l3-3L11 9.5L13.5 6m5 3H21v8h-2.5Zm0 8H21l-1.25 2.25Z");
}

.i-pa0eb3g {
  d: path("M3 3h13v11H3Zm3.5 11l-2 7.5m8-7.5l2 7.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
