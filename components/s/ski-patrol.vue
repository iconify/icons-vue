<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xpzx1ob1g"/><path class="azunmbbwk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ski-patrol" /></template>
<style>
.azunmbbwk {
  d: path("M15.48 13.98L7.5 6Q5.5 4 3 4m15.25 11v6.5M15 18.25h6.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xpzx1ob1g {
  d: path("m3.5 19l13-13q2-2 4.5-2");
}

</style>
