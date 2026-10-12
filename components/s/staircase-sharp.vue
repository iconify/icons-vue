<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uj1h7abtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:staircase-sharp" /></template>
<style>
.uj1h7abtf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 20.65V17.5h6v-3.75h6V10h6.5v11.25H2.75zm3-3.15v-5.25m6 1.5V9m6 1V5.75m-14 7.58l16-8.66");
}

</style>
