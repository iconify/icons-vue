<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="vs5a1_ubx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:police-car-fill" /></template>
<style>
.vs5a1_ubx {
  fill: currentColor;
  d: path("M96 24a8 8 0 0 1 8-8h48a8 8 0 0 1 0 16h-48a8 8 0 0 1-8-8m152 88a8 8 0 0 1-8 8h-8v80a16 16 0 0 1-16 16h-24a16 16 0 0 1-16-16v-8H80v8a16 16 0 0 1-16 16H40a16 16 0 0 1-16-16v-80h-8a8 8 0 0 1 0-16h11.36l27.39-47.94A16 16 0 0 1 68.64 48h118.72a16 16 0 0 1 13.89 8.06L228.64 104H240a8 8 0 0 1 8 8M88 144a8 8 0 0 0-8-8H56a8 8 0 0 0 0 16h24a8 8 0 0 0 8-8m120 0a8 8 0 0 0-8-8h-24a8 8 0 0 0 0 16h24a8 8 0 0 0 8-8m2.21-40l-22.85-40H68.64l-22.85 40Z");
}

</style>
