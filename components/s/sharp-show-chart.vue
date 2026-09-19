<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kt7kgiy_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-show-chart" /></template>
<style>
.kt7kgiy_n {
  fill: currentColor;
  d: path("m3.5 18.49l6-6.01l4 4L22 6.92l-1.41-1.41l-7.09 7.97l-4-4L2 16.99z");
}

</style>
