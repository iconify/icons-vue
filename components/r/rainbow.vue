<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="e1t8a6bii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:rainbow" /></template>
<style>
.e1t8a6bii {
  fill: currentColor;
  d: path("M184 168v16a8 8 0 0 1-16 0v-16a40 40 0 0 0-80 0v16a8 8 0 0 1-16 0v-16a56 56 0 0 1 112 0m-56-88a88.1 88.1 0 0 0-88 88v16a8 8 0 0 0 16 0v-16a72 72 0 0 1 144 0v16a8 8 0 0 0 16 0v-16a88.1 88.1 0 0 0-88-88m0-32A120.13 120.13 0 0 0 8 168v16a8 8 0 0 0 16 0v-16a104 104 0 0 1 208 0v16a8 8 0 0 0 16 0v-16A120.13 120.13 0 0 0 128 48");
}

</style>
