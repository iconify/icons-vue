<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="un6gk1f4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:trolley-bold" /></template>
<style>
.un6gk1f4w {
  fill: currentColor;
  d: path("M92 224a20 20 0 1 1-20-20a20 20 0 0 1 20 20m124-20a20 20 0 1 0 20 20a20 20 0 0 0-20-20m24-36H60V75.31a19.86 19.86 0 0 0-5.86-14.14L32.49 39.51a12 12 0 0 0-17 17L36 77v91h-4a12 12 0 0 0 0 24h208a12 12 0 0 0 0-24");
}

</style>
