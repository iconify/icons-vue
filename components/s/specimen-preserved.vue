<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i8l-vra6m"/><path class="ysza2bc_q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:specimen-preserved" /></template>
<style>
.i8l-vra6m {
  d: path("M7 2.5h10V6H7ZM8 6L5 9v10a2.5 2.5 0 0 0 2.5 2.5h9A2.5 2.5 0 0 0 19 19V9l-3-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ysza2bc_q {
  d: path("M9.5 18c0-5 3-7.5 5-7.5c0 5-2.5 7.5-5 7.5Z");
}

</style>
