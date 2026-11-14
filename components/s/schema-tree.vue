<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lh_-41bgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:schema-tree" /></template>
<style>
.lh_-41bgq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 3.5h2.5A1.75 1.75 0 0 1 9.5 5.25v.5A1.75 1.75 0 0 1 7.75 7.5h-2.5A1.75 1.75 0 0 1 3.5 5.75v-.5A1.75 1.75 0 0 1 5.25 3.5m8.5 6h5a1.75 1.75 0 0 1 1.75 1.75v.5a1.75 1.75 0 0 1-1.75 1.75h-5A1.75 1.75 0 0 1 12 11.75v-.5a1.75 1.75 0 0 1 1.75-1.75m0 7h5a1.75 1.75 0 0 1 1.75 1.75v.5a1.75 1.75 0 0 1-1.75 1.75h-5A1.75 1.75 0 0 1 12 18.75v-.5a1.75 1.75 0 0 1 1.75-1.75m-7.25-9v11m0-7H12m-5.5 7H12");
}

</style>
