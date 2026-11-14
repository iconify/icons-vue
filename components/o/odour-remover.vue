<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kt_gg6mrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:odour-remover" /></template>
<style>
.kt_gg6mrr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 21.5V13a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v8.5ZM6.5 11V5a1 1 0 0 1 1-1h6v3H10v4m2-4l1.75 2.25m2.75-6.5q1.25-.75 2.5 0t2.5 0m-5 3q1.25-.75 2.5 0t2.5 0m-5 3q1.25-.75 2.5 0t2.5 0");
}

</style>
