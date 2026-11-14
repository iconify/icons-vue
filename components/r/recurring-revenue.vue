<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lyyhg703l"/><path class="k2uykjb4h"/><path class="d2g9hhr1o"/><path class="ub68ubbxf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:recurring-revenue" /></template>
<style>
.d2g9hhr1o {
  d: path("M13.5 19L12 20.5l1.5 1.5m-5.75-2.639A8.5 8.5 0 0 1 12 3.5");
}

.k2uykjb4h {
  d: path("M13.5 10.25q-.375-.75-1.5-.75c-.9 0-1.5.5-1.5 1.25c0 1.5 3 1 3 2.5c0 .75-.6 1.25-1.5 1.25c-.75 0-1.3-.3-1.5-.75m5.75-9.111A8.5 8.5 0 0 1 12 20.5");
}

.lyyhg703l {
  d: path("M6.75 12a5.25 5.25 0 1 0 10.5 0a5.25 5.25 0 1 0-10.5 0Z");
}

.ub68ubbxf {
  d: path("M10.5 2L12 3.5L10.5 5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
