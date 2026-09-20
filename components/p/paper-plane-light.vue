<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="iijy86i7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:paper-plane-light" /></template>
<style>
.iijy86i7w {
  fill: currentColor;
  d: path("M236.17 201.09L140.1 33.16a14 14 0 0 0-24.41 0l-95.88 168a14 14 0 0 0 16.87 20.05L128 190.34l91.33 30.85a14.3 14.3 0 0 0 4.67.81a14 14 0 0 0 12.13-20.91Zm-10.66 8.18a1.87 1.87 0 0 1-2.2.6h-.1L134 179.7V120a6 6 0 0 0-12 0v59.7l-89.2 30.13h-.1a1.87 1.87 0 0 1-2.2-.6a1.84 1.84 0 0 1-.24-2.22L126.14 39a1.93 1.93 0 0 1 1.74-1a2 2 0 0 1 1.78 1.07L225.73 207a1.86 1.86 0 0 1-.22 2.27");
}

</style>
