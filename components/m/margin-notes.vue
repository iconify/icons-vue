<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f93j-ccio"/><path class="grepoxbrv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:margin-notes" /></template>
<style>
.f93j-ccio {
  d: path("M2.5 3h19v18h-19Zm12 0v18m-9-12h6.25M5.5 14h4");
}

.grepoxbrv {
  d: path("M18 7.5q1 1.75 0 3.5t0 3.5t0 3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
