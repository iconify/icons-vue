<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sw24vsbsh"/><path class="aye15zb9t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:scrubs" /></template>
<style>
.aye15zb9t {
  d: path("M14.5 13za1.5 1.5 0 0 1 1.5 1.5v.5a1.5 1.5 0 0 1-1.5 1.5A1.5 1.5 0 0 1 13 15v-.5a1.5 1.5 0 0 1 1.5-1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sw24vsbsh {
  d: path("m9 3l3 4l3-4l6 3l-2 4.5l-2-1v11H7v-11l-2 1L3 6Z");
}

</style>
