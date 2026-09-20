<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vepkob5yf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:subtract-parentheses-16-regular" /></template>
<style>
.vepkob5yf {
  fill: currentColor;
  d: path("M4.77 2.943a.5.5 0 1 0-.54-.842A7 7 0 0 0 1 8a7 7 0 0 0 3.23 5.898a.5.5 0 1 0 .54-.842A6 6 0 0 1 2 8a6 6 0 0 1 2.77-5.057m7-.842a.5.5 0 0 0-.54.842A6 6 0 0 1 14 8a6 6 0 0 1-2.77 5.057a.5.5 0 1 0 .54.842A7 7 0 0 0 15 8a7 7 0 0 0-3.23-5.9M5.5 7.5a.5.5 0 0 0 0 1h5a.5.5 0 0 0 0-1z");
}

</style>
