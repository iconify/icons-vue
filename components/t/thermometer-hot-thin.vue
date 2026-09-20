<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="uyl9fqb2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:thermometer-hot-thin" /></template>
<style>
.uyl9fqb2d {
  fill: currentColor;
  d: path("M124 156.29V48a4 4 0 0 0-8 0v108.29a28 28 0 1 0 8 0M120 204a20 20 0 1 1 20-20a20 20 0 0 1-20 20m36-68V48a36 36 0 0 0-72 0v88a60 60 0 1 0 72 0m-36 100a52 52 0 0 1-29.71-94.68A4 4 0 0 0 92 138V48a28 28 0 0 1 56 0v90a4 4 0 0 0 1.71 3.28A52 52 0 0 1 120 236m60.65-157.41a4 4 0 0 1 1.17-5.54c13.24-8.63 23.07-4.43 31.75-.73c8.15 3.48 14.58 6.22 24.25-.07a4 4 0 1 1 4.36 6.7C236.43 82.7 231.32 84 226.67 84c-6.06 0-11.33-2.25-16.24-4.34c-8.15-3.47-14.58-6.22-24.25.07a4 4 0 0 1-5.53-1.14m62.7 26.82a4 4 0 0 1-1.17 5.54c-5.75 3.75-10.86 5.07-15.51 5.07c-6.06 0-11.33-2.25-16.24-4.34c-8.15-3.47-14.58-6.22-24.25.07a4 4 0 1 1-4.36-6.7c13.24-8.63 23.07-4.43 31.75-.73c8.15 3.48 14.58 6.22 24.25-.07a4 4 0 0 1 5.53 1.16");
}

</style>
