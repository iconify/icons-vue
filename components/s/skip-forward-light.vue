<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="m-by_we5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:skip-forward-light" /></template>
<style>
.m-by_we5a {
  fill: currentColor;
  d: path("M200 34a6 6 0 0 0-6 6v72.84L71.37 36.14a14 14 0 0 0-14.21-.37A13.69 13.69 0 0 0 50 47.88v160.24a13.69 13.69 0 0 0 7.16 12.11a14 14 0 0 0 14.21-.37L194 143.17V216a6 6 0 0 0 12 0V40a6 6 0 0 0-6-6m-6.88 95.56L65 209.69a2 2 0 0 1-2 .05a1.79 1.79 0 0 1-1-1.62V47.88a1.79 1.79 0 0 1 1-1.62a2.1 2.1 0 0 1 1-.26a2 2 0 0 1 1 .31l128.12 80.13a1.82 1.82 0 0 1 0 3.12");
}

</style>
