<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bshqhtb0t"/><path class="mg4mvrbnk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:routing-rule" /></template>
<style>
.bshqhtb0t {
  d: path("m10.5 8l4 4l-4 4l-4-4Zm-8 4h4m4-4V5H21M10.5 16v3H21");
}

.mg4mvrbnk {
  d: path("M18.5 2.5L21 5l-2.5 2.5m0 9L21 19l-2.5 2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
