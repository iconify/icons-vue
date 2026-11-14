<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixqcf3b5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:smart-curtains" /></template>
<style>
.ixqcf3b5s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 2.5h15.5a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 19.75 6H4.25A1.75 1.75 0 0 1 2.5 4.25A1.75 1.75 0 0 1 4.25 2.5M4 6l-.5 14.5q2-1.75 3.75 0q1.75-1.75 3.5 0L10.5 6M20 6l.5 14.5q-2-1.75-3.75 0q-1.75-1.75-3.5 0L13.5 6");
}

</style>
