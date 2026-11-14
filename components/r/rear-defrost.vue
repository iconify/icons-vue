<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yp5o_kb6q"/><path class="syuw_3pbr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rear-defrost" /></template>
<style>
.syuw_3pbr {
  d: path("M8 8c-1 1.5 1 3 0 4.5s1 3 0 4.5s1 3 0 4m4-13c-1 1.5 1 3 0 4.5s1 3 0 4.5s1 3 0 4m4-13c-1 1.5 1 3 0 4.5s1 3 0 4.5s1 3 0 4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yp5o_kb6q {
  d: path("M3 3.5h18v11H3Z");
}

</style>
