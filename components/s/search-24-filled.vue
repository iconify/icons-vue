<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5o9hacpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:search-24-filled" /></template>
<style>
.m5o9hacpa {
  fill: currentColor;
  d: path("M15.843 17.368a8 8 0 1 1 1.428-1.4l4.427 4.316a1 1 0 1 1-1.396 1.432zM17 11a6 6 0 1 0-12 0a6 6 0 0 0 12 0");
}

</style>
