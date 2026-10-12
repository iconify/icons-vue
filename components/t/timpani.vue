<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wi_ms3bfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:timpani" /></template>
<style>
.wi_ms3bfv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5.75h18.5c0 4.5-4.15 8.25-9.25 8.25s-9.25-3.75-9.25-8.25m.71 3.2h17.08M7.5 12.94l-2 8.31m11-8.31l2 8.31");
}

</style>
