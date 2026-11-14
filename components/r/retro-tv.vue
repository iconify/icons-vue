<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="udnndlb4v"/><path class="c28d-okej"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:retro-tv" /></template>
<style>
.c28d-okej {
  d: path("M5.5 10.5H15V18H5.5Zm13 1h.01M18.5 15h.01");
}

.udnndlb4v {
  d: path("M2.5 7.5h19V21h-19Zm6-5l3.5 5l3.5-5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
