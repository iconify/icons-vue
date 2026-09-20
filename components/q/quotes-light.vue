<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="gy6598beq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:quotes-light" /></template>
<style>
.gy6598beq {
  fill: currentColor;
  d: path("M100 58H40a14 14 0 0 0-14 14v64a14 14 0 0 0 14 14h62v10a34 34 0 0 1-34 34a6 6 0 0 0 0 12a46.06 46.06 0 0 0 46-46V72a14 14 0 0 0-14-14m2 80H40a2 2 0 0 1-2-2V72a2 2 0 0 1 2-2h60a2 2 0 0 1 2 2Zm114-80h-60a14 14 0 0 0-14 14v64a14 14 0 0 0 14 14h62v10a34 34 0 0 1-34 34a6 6 0 0 0 0 12a46.06 46.06 0 0 0 46-46V72a14 14 0 0 0-14-14m2 80h-62a2 2 0 0 1-2-2V72a2 2 0 0 1 2-2h60a2 2 0 0 1 2 2Z");
}

</style>
