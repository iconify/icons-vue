<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s6lnlvxvf"/><path class="ptqv88b3t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:streetball" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ptqv88b3t {
  d: path("M7 14.75L9 21h6l2-6.25m-6-9.5h2a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5h-2a1.5 1.5 0 0 1-1.5-1.5a1.5 1.5 0 0 1 1.5-1.5");
}

.s6lnlvxvf {
  d: path("M6.125 2.5h11.75A2.625 2.625 0 0 1 20.5 5.125v3.25A2.625 2.625 0 0 1 17.875 11H6.125A2.625 2.625 0 0 1 3.5 8.375v-3.25A2.625 2.625 0 0 1 6.125 2.5M7 14.75a5 1 0 1 0 10 0a5 1 0 1 0-10 0");
}

</style>
