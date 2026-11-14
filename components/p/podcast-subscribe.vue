<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ikhl1g6lx"/><path class="v95kc4u5u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:podcast-subscribe" /></template>
<style>
.ikhl1g6lx {
  d: path("M7.5 2.5h4a1 1 0 0 1 1 1V12a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1V3.5a1 1 0 0 1 1-1Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v95kc4u5u {
  d: path("M3.75 10a5.75 5.75 0 0 0 11.5 0M9.5 15.75v5.75m-3.5 0h7m5-7v7m-3-3l3 3l3-3");
}

</style>
