<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="y6_f6vb2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:pentagon-thin" /></template>
<style>
.y6_f6vb2w {
  fill: currentColor;
  d: path("M223.14 90.74L135.19 22.4l-.09-.07a12 12 0 0 0-14.19 0l-.09.07l-87.95 68.34a12 12 0 0 0-4.3 13.26l32 107.7A12 12 0 0 0 72 220h112a12 12 0 0 0 11.44-8.41l32-107.53a12 12 0 0 0-4.3-13.32m-3.36 11l-32 107.54A4 4 0 0 1 184 212H72a4 4 0 0 1-3.79-2.69l-32-107.7a4 4 0 0 1 1.44-4.45l.09-.07l87.94-68.33a4 4 0 0 1 4.65 0l87.94 68.33l.09.07a4 4 0 0 1 1.42 4.53Z");
}

</style>
