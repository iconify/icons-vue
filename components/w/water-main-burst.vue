<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eif4fmbzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:water-main-burst" /></template>
<style>
.eif4fmbzf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13.5H10l-1.25 3l1.25 3H2.5Zm19 0H14l1.25 3l-1.25 3h7.5ZM12 11V3m-1.5 7.5Q8.5 6.5 5 5m8.5 5.5q2-4 5.5-5.5");
}

</style>
