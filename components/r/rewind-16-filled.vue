<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w9_o54bsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:rewind-16-filled" /></template>
<style>
.w9_o54bsb {
  fill: currentColor;
  d: path("M8 4.465a1 1 0 0 0-1.576-.818L1.412 7.183a1 1 0 0 0 0 1.634l5.012 3.536A1 1 0 0 0 8 11.536V9.232l4.424 3.12A1 1 0 0 0 14 11.537V4.465a1 1 0 0 0-1.576-.818L8 6.768z");
}

</style>
