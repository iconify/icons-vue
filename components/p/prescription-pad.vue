<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jg29_3qwt"/><path class="zjl_1_bbc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:prescription-pad" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jg29_3qwt {
  d: path("M7.5 4.5h9A3.5 3.5 0 0 1 20 8v10a3.5 3.5 0 0 1-3.5 3.5h-9A3.5 3.5 0 0 1 4 18V8a3.5 3.5 0 0 1 3.5-3.5m.5-2v4m4-4v4m4-4v4");
}

.zjl_1_bbc {
  d: path("M8.5 19.5V11h2.75c1.25 0 2.25 1 2.25 2.25c0 1-1 2-2.25 2H8.5m2.75 0l4.25 4.5m0-4l-3.25 4");
}

</style>
