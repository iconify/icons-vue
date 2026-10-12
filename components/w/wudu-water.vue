<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bh33tsb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wudu-water" /></template>
<style>
.bh33tsb4b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.85 3h8.55q.6 0 .6.6v2.3q0 .6-.6.6h-.8q-.6 0-.6-.5t-.6-.5H3.85q-.6 0-.6-.6V3.6q0-.6.6-.6M12 9c.75.9 1.25 1.6 1.25 2.2a1.25 1.25 0 0 1-2.5 0c0-.6.5-1.3 1.25-2.2m-9.25 5.75h18.5c0 3.75-3.75 6.5-9.25 6.5s-9.25-2.75-9.25-6.5m3.75 2.5h11");
}

</style>
