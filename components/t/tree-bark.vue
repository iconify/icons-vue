<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ikd_1mb8a"/><path class="jqyi9yb7v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tree-bark" /></template>
<style>
.ikd_1mb8a {
  d: path("M6 2.5h12Q16.5 7 18 12t0 9.5H6Q7.5 17 6 12t0-9.5Z");
}

.jqyi9yb7v {
  d: path("M10 5q-1 4 .25 7.5t.25 6.5m4-14q1 3.5-.5 6m.5 3.5q-1 2.5 0 4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
