<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="m7xs9v_iw"/><path class="feaeafzkb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:thermometer-simple-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.feaeafzkb {
  d: path("M136 153V88a8 8 0 0 0-16 0v65a32 32 0 1 0 16 0m-8 47a16 16 0 1 1 16-16a16 16 0 0 1-16 16m40-66V48a40 40 0 0 0-80 0v86a64 64 0 1 0 80 0m-40 98a48 48 0 0 1-27.42-87.4A8 8 0 0 0 104 138V48a24 24 0 0 1 48 0v90a8 8 0 0 0 3.42 6.56A48 48 0 0 1 128 232");
}

.m7xs9v_iw {
  d: path("M160 138V48a32 32 0 0 0-64 0v90a56 56 0 1 0 64 0m-32 70a24 24 0 1 1 24-24a24 24 0 0 1-24 24");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
