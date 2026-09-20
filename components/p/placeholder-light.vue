<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="w-dsi1pcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:placeholder-light" /></template>
<style>
.w-dsi1pcv {
  fill: currentColor;
  d: path("M208 34H48a14 14 0 0 0-14 14v160a14 14 0 0 0 14 14h160a14 14 0 0 0 14-14V48a14 14 0 0 0-14-14m2 14v153.52L54.49 46H208a2 2 0 0 1 2 2M46 208V54.48L201.51 210H48a2 2 0 0 1-2-2");
}

</style>
