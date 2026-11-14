<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ymouieb4g"/><path class="s9hdorbgn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:stream-symbol" /></template>
<style>
.s9hdorbgn {
  d: path("M9.5 2.5C9.5 8 20 6.5 20 12S9.5 16 9.5 21.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ymouieb4g {
  d: path("M4.5 2.5C4.5 8 15 6.5 15 12S4.5 16 4.5 21.5");
}

</style>
