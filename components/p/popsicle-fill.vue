<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="vq9x67y-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:popsicle-fill" /></template>
<style>
.vq9x67y-v {
  fill: currentColor;
  d: path("M128 8a72.08 72.08 0 0 0-72 72v96a16 16 0 0 0 16 16h32v40a24 24 0 0 0 48 0v-40h32a16 16 0 0 0 16-16V80a72.08 72.08 0 0 0-72-72m-16 144a8 8 0 0 1-16 0V72a8 8 0 0 1 16 0Zm24 80a8 8 0 0 1-16 0v-40h16Zm24-80a8 8 0 0 1-16 0V72a8 8 0 0 1 16 0Z");
}

</style>
