<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kh6cjybjd"/><path class="uumua7but"/><path class="i0sky3wiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rx-delivery" /></template>
<style>
.i0sky3wiv {
  d: path("M5 16.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm10.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-8-11V9");
}

.kh6cjybjd {
  d: path("M2.5 14.5h19V10l-3-3.5h-4v8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uumua7but {
  d: path("M3 5.5h9v9H3Z");
}

</style>
