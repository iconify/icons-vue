<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="svl10ac6a"/><path class="rx6tlfy_y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:noodles" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rx6tlfy_y {
  d: path("M7 14.25c.9.75 1.6.75 2.5 0s1.6-.75 2.5 0s1.6.75 2.5 0s1.6-.75 2.5 0");
}

.svl10ac6a {
  d: path("M4 10.75h16a.75.75 0 0 1 .75.8A8.75 8.75 0 0 1 16 18.7v1.55a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1V18.7a8.75 8.75 0 0 1-4.75-7.15a.75.75 0 0 1 .75-.8m5.5 0L18.25 3m-5 7.75l7-5");
}

</style>
