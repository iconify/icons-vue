<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phg6yebbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:spinner-fill-round" /></template>
<style>
.phg6yebbo {
  fill: currentColor;
  d: path("M2 12C2 6.477 6.477 2 12 2a1 1 0 0 1 0 2a7.9 7.9 0 0 0-3.114.628a8 8 0 0 0-2.543 1.715a8 8 0 0 0-2.194 7.194a7.99 7.99 0 0 0 4.737 5.835a7.99 7.99 0 0 0 8.771-1.715A7.97 7.97 0 0 0 20 12a1 1 0 0 1 2 0c0 5.523-4.477 10-10 10S2 17.523 2 12");
}

</style>
