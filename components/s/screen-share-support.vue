<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k6dkvbcqm"/><path class="dojsl9mvr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:screen-share-support" /></template>
<style>
.dojsl9mvr {
  d: path("M9 5.5L15.5 8l-3 1.25l-1.25 3ZM15.5 18a2.75 2.75 0 0 1 5.5 0m-6.25 0h2v3.5h-2Zm5 0h2v3.5h-2Z");
}

.k6dkvbcqm {
  d: path("M11.9 15.5H2.5v-13h19v11m-11 2v4m-3 0h4.4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
