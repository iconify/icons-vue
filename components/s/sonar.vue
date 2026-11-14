<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l8g95vdkq"/><path class="ifzqic-qx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sonar" /></template>
<style>
.ifzqic-qx {
  d: path("M21.192 17.692a13 13 0 0 1-18.384 0");
}

.l8g95vdkq {
  d: path("M3 4.5q3-2 6 0t6 0t6 0m-9 4h.01m3.526 3.536a5 5 0 0 1-7.072 0m9.9 2.828a9 9 0 0 1-12.728 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
