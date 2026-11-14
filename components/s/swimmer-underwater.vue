<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qfm9_-b3t"/><path class="a9xhpy77v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:swimmer-underwater" /></template>
<style>
.a9xhpy77v {
  d: path("M12.5 16.75c0-8.25 7-8.75 9-3.75");
}

.qfm9_-b3t {
  d: path("M2.5 5.5q2.375-1.75 4.75 0t4.75 0t4.75 0t4.75 0m-6.25 10a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM3 19.25L15.25 16");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
