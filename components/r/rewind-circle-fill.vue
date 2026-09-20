<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="w3f_txbxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:rewind-circle-fill" /></template>
<style>
.w3f_txbxz {
  fill: currentColor;
  d: path("M128 24a104 104 0 1 0 104 104A104.11 104.11 0 0 0 128 24m56 140a8 8 0 0 1-12.8 6.4l-48-36a8 8 0 0 1-3.2-6.4v36a8 8 0 0 1-12.8 6.4l-48-36a8 8 0 0 1 0-12.8l48-36A8 8 0 0 1 120 92v36a8 8 0 0 1 3.2-6.4l48-36A8 8 0 0 1 184 92Z");
}

</style>
