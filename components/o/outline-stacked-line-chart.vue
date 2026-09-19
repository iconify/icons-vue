<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oe7tqgb1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-stacked-line-chart" /></template>
<style>
.oe7tqgb1r {
  fill: currentColor;
  d: path("m2 19.99l7.5-7.51l4 4l7.09-7.97L22 9.92l-8.5 9.56l-4-4l-6 6.01zm1.5-4.5l6-6.01l4 4L22 3.92l-1.41-1.41l-7.09 7.97l-4-4L2 13.99z");
}

</style>
