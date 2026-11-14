<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pao7rmv1s"/><path class="jj17v8bjn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:semantic-layer" /></template>
<style>
.jj17v8bjn {
  d: path("m2.5 13.75l9.5 5.5l9.5-5.5M8.75 10l1.75-1.5h4.75v3H10.5L8.75 10");
}

.pao7rmv1s {
  d: path("m12 4.5l9.5 5.5l-9.5 5.5L2.5 10Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
