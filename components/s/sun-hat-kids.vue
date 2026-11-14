<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwn-c2b_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sun-hat-kids" /></template>
<style>
.qwn-c2b_o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7 14.5l1-7C8.25 6 9.5 5 12 5s3.75 1 4 2.5l1 7c2 1.5 4 3 4.5 4.5h-19C3 17.5 5 16 7 14.5Zm.5-3h9m-9.5 3h10");
}

</style>
