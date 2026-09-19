<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x409e7qan"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-height" /></template>
<style>
.x409e7qan {
  fill: currentColor;
  d: path("M13 6.99h1.79c.45 0 .67-.54.35-.85l-2.79-2.78a.513.513 0 0 0-.71 0L8.86 6.14c-.32.31-.1.85.35.85H11v10.02H9.21c-.45 0-.67.54-.35.85l2.79 2.78c.2.19.51.19.71 0l2.79-2.78c.32-.31.09-.85-.35-.85H13z");
}

</style>
