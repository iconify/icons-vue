<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="a3o1y7bvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:question-thin" /></template>
<style>
.a3o1y7bvm {
  fill: currentColor;
  d: path("M136 180a8 8 0 1 1-8-8a8 8 0 0 1 8 8m-8-104c-19.85 0-36 14.36-36 32v4a4 4 0 0 0 8 0v-4c0-13.23 12.56-24 28-24s28 10.77 28 24s-12.56 24-28 24a4 4 0 0 0-4 4v8a4 4 0 0 0 8 0v-4.2c18-1.77 32-15.36 32-31.8c0-17.64-16.15-32-36-32m100 52A100 100 0 1 1 128 28a100.11 100.11 0 0 1 100 100m-8 0a92 92 0 1 0-92 92a92.1 92.1 0 0 0 92-92");
}

</style>
