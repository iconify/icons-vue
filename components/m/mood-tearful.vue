<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="aupy0zyow"/><path class="zf2ivvwfc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mood-tearful" /></template>
<style>
.aupy0zyow {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0Zm5-3.25H10m4 0h2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zf2ivvwfc {
  d: path("M8.75 11.5S7.25 13 7.25 14a1.5 1.5 0 0 0 3 0c0-1-1.5-2.5-1.5-2.5Zm6.5 0s-1.5 1.5-1.5 2.5a1.5 1.5 0 0 0 3 0c0-1-1.5-2.5-1.5-2.5ZM10 18.25q2-1.75 4 0");
}

</style>
