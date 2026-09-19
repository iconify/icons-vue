<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tyqkkwbwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-show-chart" /></template>
<style>
.tyqkkwbwy {
  fill: currentColor;
  d: path("m13.5 13.48l-4-4L2 16.99l1.5 1.5l6-6.01l4 4L22 6.92l-1.41-1.41z");
}

</style>
