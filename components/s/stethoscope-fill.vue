<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="sxff6umno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:stethoscope-fill" /></template>
<style>
.sxff6umno {
  fill: currentColor;
  d: path("M240 160a32 32 0 1 0-39.93 31a8 8 0 0 0-.07 1a32 32 0 0 1-32 32h-24a32 32 0 0 1-32-32v-40.52c31.47-4 56-31.47 56-64.31V40a8 8 0 0 0-8-8h-24a8 8 0 0 0 0 16h16v39.17c0 26.58-21.25 48.49-47.36 48.83A48 48 0 0 1 56 88V48h16a8 8 0 0 0 0-16H48a8 8 0 0 0-8 8v48a64 64 0 0 0 56 63.49V192a48.05 48.05 0 0 0 48 48h24a48.05 48.05 0 0 0 48-48a8 8 0 0 0-.07-1A32 32 0 0 0 240 160m-32 8a8 8 0 1 1 8-8a8 8 0 0 1-8 8");
}

</style>
