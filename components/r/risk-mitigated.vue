<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ls5f2mbey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:risk-mitigated" /></template>
<style>
.ls5f2mbey {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.539 19H2.5L12 2.5l5.289 9.186M12 8.5v4m0 3h.01m5.99-1v7m-3-3l3 3l3-3");
}

</style>
