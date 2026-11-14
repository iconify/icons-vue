<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rq825ltwf"/><path class="b_wzrdx8j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:staging-area" /></template>
<style>
.b_wzrdx8j {
  d: path("M6 13.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm5 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm7.75 8.25C17 20 16 18.75 16 17.5a2.75 2.75 0 0 1 5.5 0c0 1.25-1 2.5-2.75 4.25Z");
}

.rq825ltwf {
  d: path("M2.5 7V3h4M10 3h4m3.5 0h4v4m-19 9.5v4h4m3.5 0h3.5M5 12V6.5h6v2h3l2.5 2.5v1Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
