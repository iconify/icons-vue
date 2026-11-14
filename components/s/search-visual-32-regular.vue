<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yrdpmz1fx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:search-visual-32-regular" /></template>
<style>
.yrdpmz1fx {
  fill: currentColor;
  d: path("M4 19a1 1 0 0 1 1 1v4.5A2.5 2.5 0 0 0 7.5 27H12a1 1 0 1 1 0 2H7.5A4.5 4.5 0 0 1 3 24.5V20a1 1 0 0 1 1-1m24 0a1 1 0 0 1 1 1v4.5a4.5 4.5 0 0 1-4.5 4.5H20a1 1 0 1 1 0-2h4.5a2.5 2.5 0 0 0 2.5-2.5V20a1 1 0 0 1 1-1m-12-7a4 4 0 1 1 0 8a4 4 0 0 1 0-8m0 2a2 2 0 1 0 0 4a2 2 0 0 0 0-4M12 3a1 1 0 1 1 0 2H7.5A2.5 2.5 0 0 0 5 7.5V12a1 1 0 1 1-2 0V7.5A4.5 4.5 0 0 1 7.5 3zm12.5 0A4.5 4.5 0 0 1 29 7.5V12a1 1 0 1 1-2 0V7.5A2.5 2.5 0 0 0 24.5 5H20a1 1 0 1 1 0-2zm-15 5a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3");
}

</style>
