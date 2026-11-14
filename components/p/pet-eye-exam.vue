<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gs--odiwv"/><path class="y4y_hr8pd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pet-eye-exam" /></template>
<style>
.gs--odiwv {
  d: path("M11.991 14.5q-4.745-.005-9.491-5q9.5-10 19 0q-1.559 1.641-3.118 2.744");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y4y_hr8pd {
  d: path("M9.5 9.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm6 10.5a2.5 1.5 0 1 0 5 0a2.5 1.5 0 1 0-5 0Zm-.75-3.75h.01M18 15h.01m3.24 1.25h.01");
}

</style>
