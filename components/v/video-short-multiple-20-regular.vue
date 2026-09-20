<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j4eeic3bq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:video-short-multiple-20-regular" /></template>
<style>
.j4eeic3bq {
  fill: currentColor;
  d: path("M14.993 4.76A3 3 0 0 1 16.001 7v6a5 5 0 0 1-5 5h-2a3 3 0 0 1-2.24-1.008q.12.008.24.008h4a4 4 0 0 0 4-4V5q0-.12-.008-.24M11 2a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3zM7 3a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h4a2 2 0 0 0 2-2V5a2 2 0 0 0-2-2zm0 4.502a1 1 0 0 1 1.514-.858l2.504 1.498a1 1 0 0 1 0 1.716l-2.504 1.498A1 1 0 0 1 7 10.498z");
}

</style>
