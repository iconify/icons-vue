<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="h6ub86btq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:math-operations-fill" /></template>
<style>
.h6ub86btq {
  fill: currentColor;
  d: path("M208 32H48a16 16 0 0 0-16 16v160a16 16 0 0 0 16 16h160a16 16 0 0 0 16-16V48a16 16 0 0 0-16-16m-61.66 45.66a8 8 0 0 1 11.32-11.32L168 76.69l10.34-10.35a8 8 0 0 1 11.32 11.32L179.31 88l10.35 10.34a8 8 0 0 1-11.32 11.32L168 99.31l-10.34 10.35a8 8 0 0 1-11.32-11.32L156.69 88ZM112 176H96v16a8 8 0 0 1-16 0v-16H64a8 8 0 0 1 0-16h16v-16a8 8 0 0 1 16 0v16h16a8 8 0 0 1 0 16m0-80H64a8 8 0 0 1 0-16h48a8 8 0 0 1 0 16m80 96h-48a8 8 0 0 1 0-16h48a8 8 0 0 1 0 16m0-32h-48a8 8 0 0 1 0-16h48a8 8 0 0 1 0 16");
}

</style>
