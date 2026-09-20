<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="t24vtgbjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:trend-down-bold" /></template>
<style>
.t24vtgbjn {
  fill: currentColor;
  d: path("M244 128v64a12 12 0 0 1-12 12h-64a12 12 0 0 1 0-24h35l-67-67l-31.51 31.52a12 12 0 0 1-17 0l-72-72a12 12 0 0 1 17-17L96 119l31.51-31.52a12 12 0 0 1 17 0L220 163v-35a12 12 0 0 1 24 0");
}

</style>
