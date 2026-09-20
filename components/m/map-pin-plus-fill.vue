<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="tykorxoor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:map-pin-plus-fill" /></template>
<style>
.tykorxoor {
  fill: currentColor;
  d: path("M128 16a88.1 88.1 0 0 0-88 88c0 31.4 14.51 64.68 42 96.25a254.2 254.2 0 0 0 41.45 38.3a8 8 0 0 0 9.18 0a254.2 254.2 0 0 0 41.37-38.3c27.45-31.57 42-64.85 42-96.25a88.1 88.1 0 0 0-88-88m32 96h-24v24a8 8 0 0 1-16 0v-24H96a8 8 0 0 1 0-16h24V72a8 8 0 0 1 16 0v24h24a8 8 0 0 1 0 16");
}

</style>
