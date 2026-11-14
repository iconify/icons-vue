<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvzb-bbtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sports-bag" /></template>
<style>
.vvzb-bbtg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 9h7.5a5.75 5.75 0 0 1 5.75 5.75a5.75 5.75 0 0 1-5.75 5.75h-7.5a5.75 5.75 0 0 1-5.75-5.75A5.75 5.75 0 0 1 8.25 9M6.5 9a5.5 5.5 0 0 1 11 0m-11 0v11.5M17.5 9v11.5");
}

</style>
