<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1mxmob6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tree-row" /></template>
<style>
.x1mxmob6q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.779 15.762l.846-5.262a1.139 1.139 0 0 1 2.25 0l.846 5.262A1.5 1.5 0 0 1 5.24 17.5h-.98a1.5 1.5 0 0 1-1.481-1.738m7.25 0l.846-5.262a1.139 1.139 0 0 1 2.25 0l.846 5.262A1.5 1.5 0 0 1 12.49 17.5h-.98a1.5 1.5 0 0 1-1.481-1.738m7.25 0l.846-5.262a1.139 1.139 0 0 1 2.25 0l.846 5.262A1.5 1.5 0 0 1 19.74 17.5h-.98a1.5 1.5 0 0 1-1.481-1.738M2.5 21h19");
}

</style>
