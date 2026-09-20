<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="hcxzcdf-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:smiley-melting-bold" /></template>
<style>
.hcxzcdf-p {
  fill: currentColor;
  d: path("M180 136a16 16 0 1 1-16-16a16 16 0 0 1 16 16m-44-44a16 16 0 1 0-16 16a16 16 0 0 0 16-16m67.83-40.9A108 108 0 0 0 47.5 200a12 12 0 0 0 17.89-16a84 84 0 1 1 125.22 0a12 12 0 0 0 17.89 16a108 108 0 0 0-4.67-148.9M140 164h-4c-19.81 0-44-16.61-44-36a36.5 36.5 0 0 1 .5-6a12 12 0 0 0-23.67-4a60.7 60.7 0 0 0-.83 10c0 16.1 8 31.46 22.49 43.25C103.58 181.9 120.17 188 136 188h4a8 8 0 0 1 0 16h-40a32 32 0 0 0-32 32a12 12 0 0 0 24 0a8 8 0 0 1 8-8h40a32 32 0 0 0 0-64");
}

</style>
