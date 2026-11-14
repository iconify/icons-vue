<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qfla-jb_m"/><path class="e-f05ob-q"/><path class="eod2xqb5u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:scrollbar-vertical" /></template>
<style>
.e-f05ob-q {
  fill: currentColor;
  d: path("M9.5 6.75h5v5h-5Z");
}

.eod2xqb5u {
  d: path("M9.5 4L12 2l2.5 2m-5 16l2.5 2l2.5-2");
}

.qfla-jb_m {
  d: path("M9.5 6.75h5v10.5h-5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
