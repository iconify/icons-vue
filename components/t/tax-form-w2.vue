<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uwivq1yig"/><path class="v3uiup95g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tax-form-w2" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uwivq1yig {
  d: path("M7 2.5h6.5l6 6V19a2.5 2.5 0 0 1-2.5 2.5H7A2.5 2.5 0 0 1 4.5 19V5A2.5 2.5 0 0 1 7 2.5Z");
}

.v3uiup95g {
  d: path("M13.5 2.5v4a2 2 0 0 0 2 2h4m-5.25 3.25C14 11 13.25 10.5 12 10.5s-2.25.75-2.25 1.75c0 2 4.5 1.25 4.5 3.5c0 1-1 1.75-2.25 1.75s-2-.5-2.25-1.25m2.25-7v1.25m0 7v1.25");
}

</style>
