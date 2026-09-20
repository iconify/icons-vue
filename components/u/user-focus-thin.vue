<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="thm3dk5ds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:user-focus-thin" /></template>
<style>
.thm3dk5ds {
  fill: currentColor;
  d: path("M220 40v36a4 4 0 0 1-8 0V44h-32a4 4 0 0 1 0-8h36a4 4 0 0 1 4 4m-4 136a4 4 0 0 0-4 4v32h-32a4 4 0 0 0 0 8h36a4 4 0 0 0 4-4v-36a4 4 0 0 0-4-4M76 212H44v-32a4 4 0 0 0-8 0v36a4 4 0 0 0 4 4h36a4 4 0 0 0 0-8M40 80a4 4 0 0 0 4-4V44h32a4 4 0 0 0 0-8H40a4 4 0 0 0-4 4v36a4 4 0 0 0 4 4m136 92a4 4 0 0 1-3.2-1.6a56 56 0 0 0-89.6 0a4 4 0 1 1-6.4-4.8a63.65 63.65 0 0 1 32.5-22.85a36 36 0 1 1 37.4 0a63.65 63.65 0 0 1 32.5 22.85a4 4 0 0 1-3.2 6.4m-48-32a28 28 0 1 0-28-28a28 28 0 0 0 28 28");
}

</style>
