<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jx7to0b6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:role-definition" /></template>
<style>
.jx7to0b6h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.197 4.211a3.5 3.5 0 0 1 1.834 1.539m.258 2.947a3.5 3.5 0 0 1-1.539 1.834m-2.947.258A3.5 3.5 0 0 1 5.969 9.25m-.258-2.947A3.5 3.5 0 0 1 7.25 4.469M3 20.5c0-2 .5-3.5 1.75-4.5m2.5-1.5c1-.25 2.5-.25 3.5 0m2.5 1.5C14.5 17 15 18.5 15 20.5m5.078-13.957za1.5 1.5 0 0 1 .897 1.922l-1.71 4.699a1.5 1.5 0 0 1-.59.743l-.628.41a.938.938 0 0 1-1.41-.513l-.217-.718a1.5 1.5 0 0 1 .026-.948l1.71-4.699a1.5 1.5 0 0 1 1.922-.896m-3.803 6.065l2.819 1.026");
}

</style>
