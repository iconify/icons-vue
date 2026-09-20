<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u0meogb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:puzzle-piece-16-regular" /></template>
<style>
.u0meogb_h {
  fill: currentColor;
  d: path("M7 3a2 2 0 0 1 4 0h1.5A1.5 1.5 0 0 1 14 4.5V7h-1a1 1 0 0 0 0 2h1v2.5a1.5 1.5 0 0 1-1.5 1.5H11a2 2 0 0 1-4 0H5.5A1.5 1.5 0 0 1 4 11.5V10a2 2 0 0 1 0-4V4.5A1.5 1.5 0 0 1 5.5 3zm2-1a1 1 0 0 0-1 1v1H5.5a.5.5 0 0 0-.5.5V7H4a1 1 0 0 0 0 2h1v2.5a.5.5 0 0 0 .5.5H8v1a1 1 0 0 0 2 0v-1h2.5a.5.5 0 0 0 .5-.5V10a2 2 0 0 1 0-4V4.5a.5.5 0 0 0-.5-.5H10V3a1 1 0 0 0-1-1");
}

</style>
