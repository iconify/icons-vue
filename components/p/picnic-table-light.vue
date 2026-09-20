<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="b1_euucge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:picnic-table-light" /></template>
<style>
.b1_euucge {
  fill: currentColor;
  d: path("M248 130h-48.29l-30-60H192a6 6 0 0 0 0-12H64a6 6 0 0 0 0 12h22.29l-30 60H8a6 6 0 0 0 0 12h42.29l-23.66 47.32a6 6 0 0 0 10.74 5.36L63.71 142h128.58l26.34 52.68a6 6 0 1 0 10.74-5.36L205.71 142H248a6 6 0 0 0 0-12m-178.29 0l30-60h56.58l30 60Z");
}

</style>
