<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwxa09bst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sun-horizon" /></template>
<style>
.gwxa09bst {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 16a5 5 0 0 1 10 0M2.5 16h19M12 4.5V8m-5.5 2.5L5 9m12.5 1.5L19 9M7 19.5h10");
}

</style>
