<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zva_bbc6c"/><path class="e85j9ubig"/><path class="kxqy7ub-o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mortgage-offset" /></template>
<style>
.e85j9ubig {
  d: path("M16 7V4h2v4.75m-3.5 9C14.5 16 16 15 18 15s3.75 1 3.75 2.75c0 1-.75 1.75-1.75 2.25v1h-1v-.75h-1.75V21H16v-1q-1.5-.75-1.5-2.25Z");
}

.kxqy7ub-o {
  d: path("M14.75 17h-1v1.25h1m1-3l.5-1.25l1 1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zva_bbc6c {
  d: path("M10.96 20.5H4v-10l8-7l8 7v1.94");
}

</style>
