<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dma_l8-zk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:swim-goggles" /></template>
<style>
.dma_l8-zk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 14.5q0-3.734 2.871-5.939Q8.394 6.625 12 6.625t6.129 1.936q2.87 2.204 2.871 5.936v.003q0 1.588-1.287 2.691q-1.236 1.059-2.963 1.059q-3.801 0-4.203-3h-1.125q-.238 1.108-1.209 1.941Q8.977 18.25 7.25 18.25Q3 18.25 3 14.5m14.215-4.749Q15.097 8.125 12 8.125T6.785 9.751q-.691.53-1.173 1.174q.72-.175 1.638-.175q1.727 0 2.963 1.059q.971.833 1.209 1.941h1.125q.402-3 4.203-3q.943 0 1.74.316q-.509-.727-1.275-1.315");
}

</style>
