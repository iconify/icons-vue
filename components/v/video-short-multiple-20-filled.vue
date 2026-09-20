<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r7bafab8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:video-short-multiple-20-filled" /></template>
<style>
.r7bafab8q {
  fill: currentColor;
  d: path("M14.993 4.76A3 3 0 0 1 16.001 7v6a5 5 0 0 1-5 5h-2a3 3 0 0 1-2.24-1.008q.12.008.24.008h4a4 4 0 0 0 4-4V5q0-.12-.008-.24M11 2a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3zM8.514 6.644A1 1 0 0 0 7 7.502v2.996a1 1 0 0 0 1.514.858l2.504-1.498a1 1 0 0 0 0-1.716z");
}

</style>
