<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="dstbz9yhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:sneaker-move-thin" /></template>
<style>
.dstbz9yhh {
  fill: currentColor;
  d: path("m229.37 170.21l-28.62-14.31A51.7 51.7 0 0 1 172 109.39V80a4 4 0 0 0-4-4a52.06 52.06 0 0 1-52-52a4 4 0 0 0-6.42-3.19l-77 58.41l-.1.08a12 12 0 0 0-.94 17.81l113.69 113.72a4 4 0 0 0 2.83 1.17H224a12 12 0 0 0 12-12v-19.06a11.94 11.94 0 0 0-6.63-10.73M228 200a4 4 0 0 1-4 4h-74.28L37.17 91.45a4 4 0 0 1 .27-5.9l15.79-12l41.26 41.25a4 4 0 0 0 5.65-5.66L59.67 68.7l48.82-37A60.12 60.12 0 0 0 164 83.87v25.52a59.68 59.68 0 0 0 33.17 53.67l28.62 14.31a4 4 0 0 1 2.21 3.57ZM70.8 180H32a4 4 0 0 1 0-8h38.8a4 4 0 1 1 0 8m36 28a4 4 0 0 1-4 4H48a4 4 0 0 1 0-8h54.8a4 4 0 0 1 4 4");
}

</style>
