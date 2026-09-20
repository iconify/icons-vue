<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k9bs2gbfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:record-16-regular" /></template>
<style>
.k9bs2gbfy {
  fill: currentColor;
  d: path("M8 12a4 4 0 1 0 0-8a4 4 0 0 0 0 8M8 1a7 7 0 1 0 0 14A7 7 0 0 0 8 1M2 8a6 6 0 1 1 12 0A6 6 0 0 1 2 8");
}

</style>
