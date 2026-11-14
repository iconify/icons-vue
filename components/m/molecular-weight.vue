<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c1ie6_sio"/><path class="zjamh_b3w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:molecular-weight" /></template>
<style>
.c1ie6_sio {
  d: path("M11.908 17.5H3l2.5-10h9l1.067 4.269");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zjamh_b3w {
  d: path("M7.75 5.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm6.75 11a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm4 3.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-1-2.5l1.25 1.25");
}

</style>
