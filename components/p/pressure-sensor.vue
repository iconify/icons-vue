<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmd0gwbwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pressure-sensor" /></template>
<style>
.wmd0gwbwf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 7.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0Zm5 5v3m-9.5 0h19m-19 5h19M12 7.5l2.25-2.25");
}

</style>
