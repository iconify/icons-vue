<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mgcey1b7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-cast-connected" /></template>
<style>
.mgcey1b7w {
  fill: currentColor;
  d: path("M1 18v3h3c0-1.66-1.34-3-3-3m0-4v2c2.76 0 5 2.24 5 5h2c0-3.87-3.13-7-7-7m18-7H5v1.63c3.96 1.28 7.09 4.41 8.37 8.37H19zM1 10v2a9 9 0 0 1 9 9h2c0-6.08-4.93-11-11-11m22-7H1v5h2V5h18v14h-7v2h9z");
}

</style>
