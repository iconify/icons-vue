<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="v2_y5xxmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:microphone-stage-fill" /></template>
<style>
.v2_y5xxmc {
  fill: currentColor;
  d: path("M115.06 46.36a4 4 0 0 0-6.11.54A71.54 71.54 0 0 0 96 88a73 73 0 0 0 .63 9.42l-69.51 94.8A15.93 15.93 0 0 0 28.71 213L43 227.29a15.93 15.93 0 0 0 20.78 1.59l94.81-69.53a73 73 0 0 0 9.41.65a71.54 71.54 0 0 0 41.09-12.93a4 4 0 0 0 .54-6.11Zm2.61 103.28l-16 16a8 8 0 1 1-11.31-11.31l16-16a8 8 0 0 1 11.31 11.31m109.4-20.56a4 4 0 0 1-6.12.54l-94.57-94.57a4 4 0 0 1 .54-6.12a71.93 71.93 0 0 1 100.15 100.15");
}

</style>
