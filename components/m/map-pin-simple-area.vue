<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="cz4nrab6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:map-pin-simple-area" /></template>
<style>
.cz4nrab6h {
  fill: currentColor;
  d: path("M120 103.2V176a8 8 0 0 0 16 0v-72.8a40 40 0 1 0-16 0m8-63.2a24 24 0 1 1-24 24a24 24 0 0 1 24-24m112 136c0 31.18-57.71 48-112 48S16 207.18 16 176c0-7.74 3.81-19.13 22-29.41c12.26-6.94 29.12-12.27 48.77-15.42a8 8 0 1 1 2.5 15.83c-17.54 2.82-33 7.63-43.42 13.55C37.05 165.5 32 171.14 32 176c0 13.36 36.52 32 96 32s96-18.64 96-32c0-4.86-5.05-10.5-13.85-15.49c-10.46-5.92-25.88-10.73-43.42-13.55a8 8 0 1 1 2.54-15.79c19.65 3.15 36.51 8.48 48.77 15.42C236.19 156.87 240 168.26 240 176");
}

</style>
