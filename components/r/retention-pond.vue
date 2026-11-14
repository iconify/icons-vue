<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w8c-lqb_g"/><path class="jts46hb1k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:retention-pond" /></template>
<style>
.jts46hb1k {
  d: path("M7.5 16q2.25-2 4.5 0t4.5 0M12 2.5v7M9.5 7L12 9.5L14.5 7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w8c-lqb_g {
  d: path("M2 12.5h2q1 8 8 8t8-8h2");
}

</style>
