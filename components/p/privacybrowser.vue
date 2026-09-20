<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cvt1y8l6s"/><path class="vb_uuxzdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:privacybrowser" /></template>
<style>
.cvt1y8l6s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 10.16a12.25 12.25 0 0 1 12.25 12.25A12.25 12.25 0 1 1 24 10.16m-2.54 2.34a10.23 10.23 0 0 0-7.22 6.81L18.07 21l1.11-3.66L22 15.66l.88-1.66ZM18.07 21l-2.69 1.4l.78 6.6a10 10 0 0 0 1.57 1.5l5.25-8Zm10.49-7.73L26.85 16l5-.18a10.4 10.4 0 0 0-3.29-2.57Zm3.85 3.33L26 19.49l.8 3.88l3.42 1l.53 5.82a10.19 10.19 0 0 0 1.71-13.57Z");
}

.vb_uuxzdb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.2 4.86L6.69 11.25V27C6.69 35.44 24 43.5 24 43.5S41.31 35.44 41.31 27V11.25L25.8 4.86a4.68 4.68 0 0 0-3.6 0");
}

</style>
