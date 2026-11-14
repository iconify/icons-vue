<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b-32qcb5c"/><path class="xywwzkkgh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wifi-6" /></template>
<style>
.b-32qcb5c {
  d: path("M3.575 7.575a10.5 10.5 0 0 1 14.85 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xywwzkkgh {
  d: path("M6.05 10.05a7 7 0 0 1 9.9 0m-7.425 2.475a3.5 3.5 0 0 1 4.95 0M11 15h.01m7.49.5l2.75 1.5v3l-2.75 1.5l-2.75-1.5v-3Z");
}

</style>
