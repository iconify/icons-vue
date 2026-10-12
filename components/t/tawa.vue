<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y348xrbda"/><path class="pfx2rvb-o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tawa" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pfx2rvb-o {
  d: path("M5 15.5c-1.5-.5-2.25.25-2.25 1s.75 1.25 2.25.75m14-1.75c1.5-.5 2.25.25 2.25 1s-.75 1.25-2.25.75m-11.5-7a4.5 1.25 0 1 0 9 0a4.5 1.25 0 1 0-9 0M10 7.5c-.6-.6.6-1.2 0-2m4 2c-.6-.6.6-1.2 0-2");
}

.y348xrbda {
  d: path("M4.5 16.25c2-2.5 13-2.5 15 0c-2 1.75-13 1.75-15 0");
}

</style>
