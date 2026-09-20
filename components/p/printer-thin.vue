<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="t6qx2fbbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:printer-thin" /></template>
<style>
.t6qx2fbbg {
  fill: currentColor;
  d: path("M214.67 76H196V40a4 4 0 0 0-4-4H64a4 4 0 0 0-4 4v36H41.33C29.57 76 20 85 20 96v80a4 4 0 0 0 4 4h36v36a4 4 0 0 0 4 4h128a4 4 0 0 0 4-4v-36h36a4 4 0 0 0 4-4V96c0-11-9.57-20-21.33-20M68 44h120v32H68Zm120 168H68v-56h120Zm40-40h-32v-20a4 4 0 0 0-4-4H64a4 4 0 0 0-4 4v20H28V96c0-6.62 6-12 13.33-12h173.34C222 84 228 89.38 228 96Zm-32-56a8 8 0 1 1-8-8a8 8 0 0 1 8 8");
}

</style>
