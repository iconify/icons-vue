<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y762zqkxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:seed-drill-row" /></template>
<style>
.y762zqkxm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 17h19m-17 0V7m0 4q-2.25 0-2.25-2.75M4.5 11q2.25 0 2.25-2.75M12 17V7m0 4q-2.25 0-2.25-2.75M12 11q2.25 0 2.25-2.75M19.5 17V7m0 4q-2.25 0-2.25-2.75M19.5 11q2.25 0 2.25-2.75");
}

</style>
