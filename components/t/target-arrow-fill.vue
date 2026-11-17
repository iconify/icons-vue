<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i583mu5wk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:target-arrow-fill" /></template>
<style>
.i583mu5wk {
  fill: currentColor;
  d: path("M12.707 12.707a.999.999 0 1 1-1.414-1.414L16 6.586V3a1 1 0 0 1 2 0v1.586l2.293-2.293a.999.999 0 1 1 1.414 1.414L19.414 6H21a1 1 0 0 1 0 2h-3.586ZM22 12c0 5.523-4.477 10-10 10S2 17.523 2 12S6.477 2 12 2a1 1 0 0 1 0 2a7.9 7.9 0 0 0-3.114.628a8 8 0 0 0-2.543 1.715a8 8 0 0 0-2.194 7.194a7.99 7.99 0 0 0 4.737 5.835a7.99 7.99 0 0 0 8.771-1.715A7.97 7.97 0 0 0 20 12a1 1 0 0 1 2 0m-4 0a6 6 0 1 1-12 0c0-1.596.627-3.117 1.757-4.243a6 6 0 0 1 1.907-1.285A5.9 5.9 0 0 1 12 6a1 1 0 0 1 0 2a4 4 0 0 0-3.696 2.471a3.99 3.99 0 0 0 .868 4.357A4 4 0 0 0 16 12a1 1 0 0 1 2 0");
}

</style>
