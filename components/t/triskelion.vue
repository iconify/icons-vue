<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yuyx5eabn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:triskelion" /></template>
<style>
.yuyx5eabn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12.5a4.13 4.13 0 0 1 0-8.25a2.25 2.25 0 0 1 0 4.5m0 3.75a4.13 4.13 0 0 1 7.14 4.13a2.25 2.25 0 0 1-3.89-2.25M12 12.5a4.13 4.13 0 0 1-7.14 4.13a2.25 2.25 0 0 1 3.89-2.25");
}

</style>
