<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="m3bg3tb9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:subtract-bold" /></template>
<style>
.m3bg3tb9u {
  fill: currentColor;
  d: path("M178 78A84 84 0 1 0 78 178A84 84 0 1 0 178 78m42 82a61 61 0 0 1-.38 6.65l-44-44a83.6 83.6 0 0 0 4-19.39A59.83 59.83 0 0 1 220 160M36 96a60 60 0 1 1 60 60a60.07 60.07 0 0 1-60-60m67.28 83.66a83.6 83.6 0 0 0 19.39-4l44 44a61 61 0 0 1-6.67.34a59.83 59.83 0 0 1-56.72-40.34m88.53 31.18l-46.73-46.73a85 85 0 0 0 19-19l46.73 46.73a60.45 60.45 0 0 1-19 19");
}

</style>
