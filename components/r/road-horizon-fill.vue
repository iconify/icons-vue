<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="rkvu9nlae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:road-horizon-fill" /></template>
<style>
.rkvu9nlae {
  fill: currentColor;
  d: path("M239 188.08L173.68 72h58a8.17 8.17 0 0 0 8.32-7.47a8 8 0 0 0-8-8.53H24.27A8.17 8.17 0 0 0 16 63.47A8 8 0 0 0 24 72h58.32L17 188.08a8 8 0 0 0 1.17 9.43a8.24 8.24 0 0 0 6 2.49H116a4 4 0 0 0 4-4v-19.73a8.17 8.17 0 0 1 7.47-8.25a8 8 0 0 1 8.53 8v20a4 4 0 0 0 4 4h91.77a8.24 8.24 0 0 0 6-2.49a8 8 0 0 0 1.23-9.45M136 140a8 8 0 0 1-16 0v-16a8 8 0 0 1 16 0Zm0-52a8 8 0 0 1-16 0v-8a8 8 0 0 1 16 0Z");
}

</style>
