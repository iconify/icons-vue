<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="td2041mkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:picnic-blanket" /></template>
<style>
.td2041mkn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 9.5a5.5 5.5 0 0 1 11 0m-13 0h15A1.5 1.5 0 0 1 21 11a1.5 1.5 0 0 1-1.5 1.5h-15A1.5 1.5 0 0 1 3 11a1.5 1.5 0 0 1 1.5-1.5m0 3l1.5 8h12l1.5-8m-14.25 4h13.5");
}

</style>
