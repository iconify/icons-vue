<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="za9stvb_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:superset-proper-of-bold" /></template>
<style>
.za9stvb_y {
  fill: currentColor;
  d: path("M228 128a92.1 92.1 0 0 1-92 92H64a12 12 0 0 1 0-24h72a68 68 0 0 0 0-136H64a12 12 0 0 1 0-24h72a92.1 92.1 0 0 1 92 92");
}

</style>
