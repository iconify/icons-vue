<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ug95o6kvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shell-completion" /></template>
<style>
.ug95o6kvi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3L7 6.5L3.5 10m6 0H14m-3 3h7a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5h-7A3.5 3.5 0 0 1 7.5 18v-1.5A3.5 3.5 0 0 1 11 13m-.5 3H18m-7.5 2.75h5");
}

</style>
