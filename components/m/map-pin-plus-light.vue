<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="cda579bcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:map-pin-plus-light" /></template>
<style>
.cda579bcq {
  fill: currentColor;
  d: path("M166 104a6 6 0 0 1-6 6h-26v26a6 6 0 0 1-12 0v-26H96a6 6 0 0 1 0-12h26V72a6 6 0 0 1 12 0v26h26a6 6 0 0 1 6 6m48 0c0 30.91-14.34 63.74-41.47 94.94a252.3 252.3 0 0 1-41.09 38a6 6 0 0 1-6.88 0a252.3 252.3 0 0 1-41.09-38C56.34 167.74 42 134.91 42 104a86 86 0 0 1 172 0m-12 0a74 74 0 0 0-148 0c0 59.62 59 108.93 74 120.51c15-11.58 74-60.89 74-120.51");
}

</style>
