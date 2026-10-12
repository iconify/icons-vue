<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="inqcjm15q"/><path class="svmqi3b-n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:strawberry-sharp" /></template>
<style>
.inqcjm15q {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21.25c-3.75-1.5-7.75-5-7.75-9C4.25 10 6 8.5 8.25 8.5c1.5 0 2.5.5 3.75.5s2.25-.5 3.75-.5c2.25 0 4 1.5 4 3.75c0 4-4 7.5-7.75 9ZM12 9L8.75 5.5M12 9l3.25-3.5M12 9V2.75");
}

.svmqi3b-n {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 12h.01M15 12h.01M12 14.75h.01M10 17.25h.01m3.99 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
