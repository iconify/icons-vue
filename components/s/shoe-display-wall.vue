<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qovb3cc8c"/><path class="hmen-bbsn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shoe-display-wall" /></template>
<style>
.hmen-bbsn {
  d: path("M17.5 10.75c-.5.75-.5 1.5-.25 2.25m-8-4.25l3 1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qovb3cc8c {
  d: path("M2.5 2.5v19m0-6H13m-10.5 4l4-4M6 13V8.5c0-1 1-1.5 2-1.25L11 8l3.5 2.25c3.5.5 7 1 7 2.75Zm1.25 0h13a1.25 1.25 0 0 1 1.25 1.25a1.25 1.25 0 0 1-1.25 1.25h-13A1.25 1.25 0 0 1 6 14.25A1.25 1.25 0 0 1 7.25 13");
}

</style>
