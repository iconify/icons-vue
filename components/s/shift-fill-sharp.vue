<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkr0f1b4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shift-fill-sharp" /></template>
<style>
.wkr0f1b4s {
  fill: currentColor;
  d: path("M15 20H9a1 1 0 0 1-1-1v-5H4a1.002 1.002 0 0 1-.707-1.707l8-8a1 1 0 0 1 1.414 0l8 8A1 1 0 0 1 20 14h-4v5a1 1 0 0 1-1 1");
}

</style>
