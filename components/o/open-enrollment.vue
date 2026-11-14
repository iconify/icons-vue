<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rbgfucfga"/><path class="wq22_2tdz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:open-enrollment" /></template>
<style>
.rbgfucfga {
  d: path("M2.5 2.5h19v19h-19Zm0 3h19m-19 3h19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wq22_2tdz {
  d: path("M6 14h12v7.5H6Zm6 0v7.5m0-7.5c-1.25-2.25-3.5-2.75-3.5-1.25c0 1 2 1.25 3.5 1.25s3.5-.25 3.5-1.25c0-1.5-2.25-1-3.5 1.25Z");
}

</style>
