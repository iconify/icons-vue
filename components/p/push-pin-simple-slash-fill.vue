<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="dg3c13b3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:push-pin-simple-slash-fill" /></template>
<style>
.dg3c13b3u {
  fill: currentColor;
  d: path("M79.25 38.69a4 4 0 0 1 3-6.69H192a8 8 0 0 1 8 8.53a8.17 8.17 0 0 1-8.27 7.47h-6.19l21.16 119.91a4 4 0 0 1-6.9 3.39Zm134.67 171.93l-160-176a8 8 0 1 0-11.84 10.76L66.24 72l-16.95 96H40a8 8 0 0 0 0 16h80v56a8 8 0 0 0 16 0v-56h32.1l34 37.38a8 8 0 1 0 11.84-10.76Z");
}

</style>
