<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihamgpx2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mortgage-paid-off" /></template>
<style>
.ihamgpx2h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.611 13.476l5.25-4.5a1.75 1.75 0 0 1 2.278 0l5.25 4.5A1.75 1.75 0 0 1 19 14.805v4.945a1.75 1.75 0 0 1-1.75 1.75H6.75A1.75 1.75 0 0 1 5 19.75v-4.945a1.75 1.75 0 0 1 .611-1.329m-.987-9.388za.875.875 0 0 1 .523 1.121a.875.875 0 0 1-1.122.523a.875.875 0 0 1-.523-1.121a.875.875 0 0 1 1.122-.523M9 2.75h.01M12.5 4.5c.75-1.5 2 1 3-.5q.75-1.125 1.5-.75m2.296 2.767za.875.875 0 0 1 1.163.424a.875.875 0 0 1-.423 1.162a.875.875 0 0 1-1.163-.423a.875.875 0 0 1 .423-1.163M21 11h.01M3 10.25h.01m3.49-2c.5-1 1.5 0 2.25-1.25");
}

</style>
