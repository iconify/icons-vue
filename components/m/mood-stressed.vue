<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b0el-4y_n"/><path class="kle-t79et"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mood-stressed" /></template>
<style>
.b0el-4y_n {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0ZM7 7.75l3 1.5m7-1.5l-3 1.5M9 12h.01M15 12h.01");
}

.kle-t79et {
  d: path("m7.5 16.5l1.5-1l1.5 1l1.5-1l1.5 1l1.5-1l1.5 1Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
