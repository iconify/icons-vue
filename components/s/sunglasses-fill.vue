<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="dl0u5qbvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:sunglasses-fill" /></template>
<style>
.dl0u5qbvi {
  fill: currentColor;
  d: path("M200 40a8 8 0 0 0 0 16a16 16 0 0 1 16 16v56H40V72a16 16 0 0 1 16-16a8 8 0 0 0 0-16a32 32 0 0 0-32 32v92a44 44 0 0 0 88 0v-20h32v20a44 44 0 0 0 88 0V72a32 32 0 0 0-32-32M91.22 179.22a8 8 0 0 1-11.31 0l-21.57-21.56a8 8 0 0 1 11.32-11.32l21.56 21.57a8 8 0 0 1 0 11.31m120 0a8 8 0 0 1-11.31 0l-21.57-21.56a8 8 0 0 1 11.32-11.32l21.56 21.57a8 8 0 0 1 0 11.31");
}

</style>
