<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uegfqnf7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sort-az" /></template>
<style>
.uegfqnf7v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.5 10.5l2.75-7l2.75 7M14.5 8H18m-4.5 5.5H19l-5.5 7H19M7 4v16m-3-3l3 3l3-3");
}

</style>
