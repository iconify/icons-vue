<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="c0rs7nbsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:x-logo-fill" /></template>
<style>
.c0rs7nbsz {
  fill: currentColor;
  d: path("M215 219.85a8 8 0 0 1-7 4.15h-48a8 8 0 0 1-6.75-3.71l-40.49-63.63l-58.84 64.72a8 8 0 0 1-11.84-10.76l61.77-68l-62.6-98.32A8 8 0 0 1 48 32h48a8 8 0 0 1 6.75 3.71l40.49 63.63l58.84-64.72a8 8 0 0 1 11.84 10.76l-61.77 67.95l62.6 98.38a8 8 0 0 1 .25 8.14");
}

</style>
