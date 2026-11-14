<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yro2r43sv"/><path class="j07jbebtx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sleep-apnea-test" /></template>
<style>
.j07jbebtx {
  d: path("M14.2 14H9V9h6v4.3m4.75.95c-2.5.25-4.5 2-4.5 4.25c0 1.75 1.5 3.25 3.5 3.25c1.5 0 2.5-.75 3-1.75c-2.5 0-4-1.75-3.5-3.75c.25-1 .75-1.5 1.5-2Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yro2r43sv {
  d: path("M9.5 2.5c0 1.75-1.25 2.5-3 3L5 6c-1.25.5-1.75 1.25-1.5 2.5l2.25 5c.25 1-.5 4-.5 8h8.014m5.888-10.005L20.5 8.5c.25-1.25-.25-2-1.5-2.5l-1.5-.5c-1.75-.5-3-1.25-3-3m-9 9H9m6 0h3.5");
}

</style>
