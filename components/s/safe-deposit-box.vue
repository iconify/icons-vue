<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w7mc2oblu"/><path class="fx9g0t2jw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:safe-deposit-box" /></template>
<style>
.fx9g0t2jw {
  d: path("M5.5 6.5h5v3h-5Zm8 0h5v3h-5Zm-8 5h5v3h-5Zm8 0h5v3h-5Zm-8 5h5v3h-5Zm8 0h5v3h-5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w7mc2oblu {
  d: path("M3 4h18v16H3Z");
}

</style>
