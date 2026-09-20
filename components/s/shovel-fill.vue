<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="chol95brd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:shovel-fill" /></template>
<style>
.chol95brd {
  fill: currentColor;
  d: path("M245.66 69.66a8 8 0 0 1-11.32 0L216 51.31l-71 71L133.66 111l71-71l-18.32-18.34a8 8 0 0 1 11.32-11.32l48 48a8 8 0 0 1 0 11.32M88 176a8 8 0 0 1-5.66-13.66L133.66 111L99.31 76.68a16 16 0 0 0-22.62 0l-56 56A15.9 15.9 0 0 0 16 144v80a16 16 0 0 0 16 16h80a15.86 15.86 0 0 0 11.31-4.69l56-56a16 16 0 0 0 0-22.62L145 122.34l-51.34 51.32A8 8 0 0 1 88 176");
}

</style>
