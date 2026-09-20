<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h3laydbah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:more-circle-16-filled" /></template>
<style>
.h3laydbah {
  fill: currentColor;
  d: path("M8 14A6 6 0 1 0 8 2a6 6 0 0 0 0 12m0-5a1 1 0 1 1 0-2a1 1 0 0 1 0 2m4-1a1 1 0 1 1-2 0a1 1 0 0 1 2 0M5 9a1 1 0 1 1 0-2a1 1 0 0 1 0 2");
}

</style>
