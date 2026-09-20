<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="a_tlkccug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:trend-down-thin" /></template>
<style>
.a_tlkccug {
  fill: currentColor;
  d: path("M236 128v64a4 4 0 0 1-4 4h-64a4 4 0 0 1 0-8h54.34L136 101.66l-37.17 37.17a4 4 0 0 1-5.66 0l-72-72a4 4 0 0 1 5.66-5.66L96 130.34l37.17-37.17a4 4 0 0 1 5.66 0L228 182.34V128a4 4 0 0 1 8 0");
}

</style>
