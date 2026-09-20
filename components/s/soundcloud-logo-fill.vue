<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="a3vjbpp4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:soundcloud-logo-fill" /></template>
<style>
.a3vjbpp4h {
  fill: currentColor;
  d: path("M24 120v48a8 8 0 0 1-16 0v-48a8 8 0 0 1 16 0m24-32a8 8 0 0 0-8 8v96a8 8 0 0 0 16 0V96a8 8 0 0 0-8-8m32-8a8 8 0 0 0-8 8v104a8 8 0 0 0 16 0V88a8 8 0 0 0-8-8m32-32a8 8 0 0 0-8 8v136a8 8 0 0 0 16 0V56a8 8 0 0 0-8-8m110.84 58.34A80 80 0 0 0 144 40h-4a4 4 0 0 0-4 4v152a4 4 0 0 0 4 4h67.21c25.58 0 47.27-19.72 48.71-45.26a48.06 48.06 0 0 0-33.08-48.4");
}

</style>
