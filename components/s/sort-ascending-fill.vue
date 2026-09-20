<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="fa4b11b5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:sort-ascending-fill" /></template>
<style>
.fa4b11b5r {
  fill: currentColor;
  d: path("M208 32H48a16 16 0 0 0-16 16v160a16 16 0 0 0 16 16h160a16 16 0 0 0 16-16V48a16 16 0 0 0-16-16M72 72h96a8 8 0 0 1 0 16H72a8 8 0 0 1 0-16m40 112H72a8 8 0 0 1 0-16h40a8 8 0 0 1 0 16m8-48H72a8 8 0 0 1 0-16h48a8 8 0 0 1 0 16m77.66 29.66l-24 24a8 8 0 0 1-11.32 0l-24-24a8 8 0 0 1 11.32-11.32L160 164.69V120a8 8 0 0 1 16 0v44.69l10.34-10.35a8 8 0 0 1 11.32 11.32");
}

</style>
