<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qc2siwrsj"/><path class="xp0v7cbit"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:user-journey" /></template>
<style>
.qc2siwrsj {
  d: path("M17 13.5S13 10 13 7a4.25 4.25 0 0 1 8.25 0c0 3-4.25 6.5-4.25 6.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xp0v7cbit {
  d: path("M15.5 7a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM3 20.5h.01M6 20h.01m2.74-1.25h.01m1.24-2.5h.01m-1.51-2.5h.01M7 11.25h.01M8 8.75h.01m2.24-1.5h.01M17 16.5h.01");
}

</style>
