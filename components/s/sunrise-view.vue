<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hy-geudmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sunrise-view" /></template>
<style>
.hy-geudmt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 18a7 7 0 0 1 14 0M2.5 18h19M12 6v2m-8 2l1.75 1.5M20 10l-1.75 1.5M8 21.5h8");
}

</style>
