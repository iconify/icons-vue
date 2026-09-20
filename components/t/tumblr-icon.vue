<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":446};
const content = `<path class="thliscbwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:tumblr-icon" /></template>
<style>
.thliscbwq {
  fill: var(--svg-color--303d4d, #303d4d);
  d: path("M234.576 355.8c-8.28 3.95-24.125 7.387-35.953 7.7c-35.64.959-42.56-25.04-42.872-43.921V180.922H245.2v-67.42h-89.113V.042H90.831c-1.071 0-2.946.937-3.192 3.325C83.823 38.093 67.554 99.041 0 123.39v57.533h45.08v145.553c0 49.812 36.757 120.602 133.792 118.95c32.717-.558 69.072-14.283 77.128-26.088z");
}

</style>
