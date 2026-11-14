<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="iloc6ub9m"/><path class="mwl6-mb8y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:schedule-viewing" /></template>
<style>
.iloc6ub9m {
  d: path("M11.7 21.5H5v-19h12.5v8.9");
}

.mwl6-mb8y {
  d: path("M14.5 15.5h7v6.25h-7Zm0 2.5h7m-4.75-3.75v2.25m2.5-2.25v2.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
