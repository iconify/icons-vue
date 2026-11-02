<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="clmwe_b2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-lock-fill" /></template>
<style>
.clmwe_b2h {
  fill: currentColor;
  d: path("M18 2a3 3 0 0 1 3 3v5c-.001 5.712-3.495 9.647-8.594 11.914a1 1 0 0 1-.812 0C6.495 19.647 3.001 15.712 3 10V5a3 3 0 0 1 3-3Zm-3 7.267V9a3 3 0 1 0-6 0v.267A2 2 0 0 0 8 11v2a2 2 0 0 0 2 2h4a2 2 0 0 0 2-2v-2c0-.715-.38-1.376-1-1.733M13 9h-2a1 1 0 0 1 2 0");
}

</style>
