<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p3kuxrn7b"/><path class="v7bhsfouk"/><path class="bsl0ynbqn"/><path class="zf65bnmhy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:swimmer-open-water" /></template>
<style>
.bsl0ynbqn {
  d: path("M2.5 15.5q2.75-2.5 5.5 0t5.5 0t5.5 0q1.25 1.25 2.5 0");
}

.p3kuxrn7b {
  d: path("M8.5 11.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v7bhsfouk {
  d: path("M16.25 14.25C16.5 5.5 7 2.5 3.5 8.5");
}

.zf65bnmhy {
  d: path("M5 19.25q2.5-2 5 0t5 0t5 0");
}

</style>
