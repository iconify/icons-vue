<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r80wqt2kv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:public-fountain" /></template>
<style>
.r80wqt2kv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 13h16q-.5 4-8 4t-8-4m4 8h8m-4-4v4m0-18v7.25m-2.75 0q-.75-5.75-4.5 0m10 0q.75-5.75 4.5 0");
}

</style>
