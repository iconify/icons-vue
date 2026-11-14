<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8w8l7b2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:window-function" /></template>
<style>
.l8w8l7b2o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 2.5h2.5a1.75 1.75 0 0 1 1.75 1.75v15.5a1.75 1.75 0 0 1-1.75 1.75h-2.5a1.75 1.75 0 0 1-1.75-1.75V4.25A1.75 1.75 0 0 1 9.25 2.5M7.5 6.25h6M7.5 10h6m-6 4h6m-6 3.75h6M6 6.25H4.5v11.5H6m9-11.5h1.5v11.5H15M19.75 6.5v11M18 15.75l1.75 1.75l1.75-1.75");
}

</style>
