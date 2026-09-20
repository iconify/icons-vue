<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="utuyvrdms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:spinner-ios-16-regular" /></template>
<style>
.utuyvrdms {
  fill: currentColor;
  d: path("M2 8a6 6 0 1 1 6 6a.5.5 0 0 0 0 1a7 7 0 1 0-7-7a.5.5 0 0 0 1 0");
}

</style>
