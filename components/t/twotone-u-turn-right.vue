<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yuh3zub3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-u-turn-right" /></template>
<style>
.yuh3zub3d {
  fill: currentColor;
  d: path("M6 9v12h2V9c0-2.21 1.79-4 4-4s4 1.79 4 4v4.17l-1.59-1.59L13 13l4 4l4-4l-1.41-1.41L18 13.17V9c0-3.31-2.69-6-6-6S6 5.69 6 9");
}

</style>
