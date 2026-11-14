<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="em0pxi22k"/><path class="y5sxu_l7f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:scalpel" /></template>
<style>
.em0pxi22k {
  d: path("M10.75 11.25L18.25 5c.5-.5 1.25-.5 2 .25c.5.5.25 1.25-.25 2l-7.5 6.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y5sxu_l7f {
  d: path("m10.5 11l-4.25 3.75c-2.25 1.75-2.5 4-1.25 5.5l7.75-6.5Z");
}

</style>
