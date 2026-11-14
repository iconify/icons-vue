<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hg8y31bct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:welcome-kit" /></template>
<style>
.hg8y31bct {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.75 7.257q.982.071 1.658.826q.745.832.621 1.943l-1.111 10q-.246 2.224-2.484 2.224H6.566q-2.238 0-2.484-2.224l-1.111-10q-.124-1.111.621-1.943q.676-.755 1.658-.826V5q.001-2.999 3-2.999t3 2.999v2.25h1.5V5q0-3 3-3t3 3zm-4.5-.007h3V5q0-1.5-1.5-1.5T14.25 5zM6.75 5v2.25h3V5q-.001-1.499-1.5-1.499T6.75 5m4.814 14.11q.047.034.1.06q.052.026.107.044q.056.018.113.027q.058.009.116.009t.116-.009t.113-.027t.107-.044t.1-.06Q16 16.565 16 14.25q0-3-3-3q-.569 0-1 .318q-.431-.318-1-.318q-3 0-3 3q0 2.315 3.564 4.86");
}

</style>
