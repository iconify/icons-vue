<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zr47fgb8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-fill-round" /></template>
<style>
.zr47fgb8g {
  fill: currentColor;
  d: path("M7 7a5 5 0 1 1 10.001.001A5 5 0 0 1 7 7m11 15H6a1 1 0 0 1-1-1a6.9 6.9 0 0 1 .551-2.725A6.9 6.9 0 0 1 7.05 16.05A6.97 6.97 0 0 1 12 14c1.862 0 3.636.731 4.95 2.05a6.9 6.9 0 0 1 1.499 2.225c.366.862.554 1.789.551 2.725a1 1 0 0 1-1 1");
}

</style>
