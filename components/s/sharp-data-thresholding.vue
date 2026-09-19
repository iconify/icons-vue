<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vsxh5-bzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-data-thresholding" /></template>
<style>
.vsxh5-bzf {
  fill: currentColor;
  d: path("M21 3H3v18h18zM10.67 8.17l2 2l3.67-3.67l1.41 1.41L12.67 13l-2-2l-3 3l-1.41-1.41zM5 16h1.72L5 17.72zm.84 3l3-3h1.83l-3 3zm3.96 0l3-3h1.62l-3 3zm3.73 0l3-3h1.62l-3 3zM19 19h-1.73L19 17.27z");
}

</style>
