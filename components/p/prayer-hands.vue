<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4_qrwywp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:prayer-hands" /></template>
<style>
.y4_qrwywp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 18V4.75a1.75 1.75 0 0 0-3.5 0v5.5c-1.5 1-2.25 2.5-2.25 4.25c0 1.5.5 2.75 1.5 3.5Zm3 0V4.75a1.75 1.75 0 0 1 3.5 0v5.5c1.5 1 2.25 2.5 2.25 4.25c0 1.5-.5 2.75-1.5 3.5Zm-7.25 3h11.5");
}

</style>
