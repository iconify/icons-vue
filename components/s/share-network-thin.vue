<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="yku5708ds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:share-network-thin" /></template>
<style>
.yku5708ds {
  fill: currentColor;
  d: path("M176 164a36 36 0 0 0-27.92 13.3L96.25 144a35.92 35.92 0 0 0 0-32l51.83-33.3a35.93 35.93 0 1 0-4.33-6.7l-51.83 33.3a36 36 0 1 0 0 45.4l51.83 33.3A36 36 0 1 0 176 164m0-136a28 28 0 1 1-28 28a28 28 0 0 1 28-28M64 156a28 28 0 1 1 28-28a28 28 0 0 1-28 28m112 72a28 28 0 1 1 28-28a28 28 0 0 1-28 28");
}

</style>
