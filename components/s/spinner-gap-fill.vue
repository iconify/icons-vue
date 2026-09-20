<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="yrz4xe06m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:spinner-gap-fill" /></template>
<style>
.yrz4xe06m {
  fill: currentColor;
  d: path("M128 24a104 104 0 1 0 104 104A104.11 104.11 0 0 0 128 24M48 136a8 8 0 0 1 0-16h24a8 8 0 0 1 0 16Zm46.06 37.25l-17 17a8 8 0 0 1-11.32-11.32l17-17a8 8 0 0 1 11.31 11.31Zm0-79.19a8 8 0 0 1-11.31 0l-17-17a8 8 0 0 1 11.34-11.29l17 17a8 8 0 0 1-.03 11.29M136 208a8 8 0 0 1-16 0v-24a8 8 0 0 1 16 0Zm0-136a8 8 0 0 1-16 0V48a8 8 0 0 1 16 0Zm54.23 118.23a8 8 0 0 1-11.32 0l-17-17a8 8 0 0 1 11.31-11.31l17 17a8 8 0 0 1 .01 11.31M208 136h-24a8 8 0 0 1 0-16h24a8 8 0 0 1 0 16");
}

</style>
