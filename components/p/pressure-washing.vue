<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zda7_63na"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pressure-washing" /></template>
<style>
.zda7_63na {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9H10v4.5H7L6 19H3l.75-5.5H2.5Zm19-5.5v17M14 8.25l4.75-2m-4.25 5h4.25m-4.75 3l4.75 2");
}

</style>
