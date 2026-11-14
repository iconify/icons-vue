<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="awwjx98hj"/><path class="xw9lkt1ln"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:white-blood-cell" /></template>
<style>
.awwjx98hj {
  d: path("M12 2.5c3-.25 5.75 1.25 7.25 3.75C21 8.75 21.75 12 21 14.75c-.75 3-3 5.5-6 6.5c-3 .75-6 0-8.25-1.75c-2.5-2-4.25-4.5-4.25-7.5s1-5.75 3.5-7.5c1.75-1.25 3.75-2 6-2Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xw9lkt1ln {
  fill: currentColor;
  d: path("M9 8c1.5-.75 2.75 0 3.25.75c.75-1.5 3.25-1.75 4.25 0s-.25 3.5-1.75 3.75c1 1.25.5 4-1.75 4.25c-2 .25-3-1.5-2.5-3.25c-1.75.25-3.5-1-3.5-2.75C7 9.5 7.75 8.5 9 8Z");
}

</style>
