<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wby8cvb-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:translate" /></template>
<style>
.wby8cvb-g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 5.75h9m-4.5-2v2m2.75 0c-.6 3.65-3 6.5-6.75 8m2.25-4.5c1 1.75 2.5 3 4.25 3.75m2 7.25l3.75-9l3.75 9m-6.25-3h5");
}

</style>
