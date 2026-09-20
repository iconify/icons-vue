<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="pcoxjkqsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:users-four-bold" /></template>
<style>
.pcoxjkqsz {
  fill: currentColor;
  d: path("M24.79 121.59a12 12 0 0 0 16.81-2.38a48 48 0 0 1 76.81 0a12 12 0 0 0 16.8 2.39a12.2 12.2 0 0 0 2.38-2.39a48 48 0 0 1 76.81 0a12 12 0 1 0 19.19-14.41a72 72 0 0 0-25.3-21.22a40 40 0 1 0-64.58 0A71 71 0 0 0 128 94.31a71 71 0 0 0-15.71-10.74a40 40 0 1 0-64.58 0a72 72 0 0 0-25.3 21.22a12 12 0 0 0 2.38 16.8M176 44a16 16 0 1 1-16 16a16 16 0 0 1 16-16m-96 0a16 16 0 1 1-16 16a16 16 0 0 1 16-16m128.29 151.57a40 40 0 1 0-64.58 0A71.3 71.3 0 0 0 128 206.3a71.3 71.3 0 0 0-15.71-10.73a40 40 0 1 0-64.58 0a72 72 0 0 0-25.3 21.22a12 12 0 0 0 19.19 14.42a48 48 0 0 1 76.81 0a12 12 0 0 0 16.8 2.39a12.2 12.2 0 0 0 2.38-2.39a48 48 0 0 1 76.81 0a12 12 0 1 0 19.19-14.41a71.9 71.9 0 0 0-25.3-21.23M80 156a16 16 0 1 1-16 16a16 16 0 0 1 16-16m96 0a16 16 0 1 1-16 16a16 16 0 0 1 16-16");
}

</style>
