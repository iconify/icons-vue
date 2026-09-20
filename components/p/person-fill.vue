<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="a41qt7bbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:person-fill" /></template>
<style>
.a41qt7bbz {
  fill: currentColor;
  d: path("M100 36a28 28 0 1 1 28 28a28 28 0 0 1-28-28m115.42 104.78l-45.25-51.3a28 28 0 0 0-21-9.48h-42.34a28 28 0 0 0-21 9.48l-45.25 51.3a16 16 0 0 0 22.56 22.69L89 142.7l-19.7 74.88a16 16 0 0 0 29.08 13.35L128 180l29.58 51a16 16 0 0 0 29.08-13.35L167 142.7l25.9 20.77a16 16 0 0 0 22.56-22.69Z");
}

</style>
