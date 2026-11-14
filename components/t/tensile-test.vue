<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-412_bif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tensile-test" /></template>
<style>
.r-412_bif {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 9.5h.5A1.75 1.75 0 0 1 7 11.25v7.5a1.75 1.75 0 0 1-1.75 1.75h-.5A1.75 1.75 0 0 1 3 18.75v-7.5A1.75 1.75 0 0 1 4.75 9.5m14 0h.5A1.75 1.75 0 0 1 21 11.25v7.5a1.75 1.75 0 0 1-1.75 1.75h-.5A1.75 1.75 0 0 1 17 18.75v-7.5a1.75 1.75 0 0 1 1.75-1.75M7 13.5h10m-10 3h10m-7-12H3m2-2l-2 2l2 2m9-2h7m-2-2l2 2l-2 2");
}

</style>
