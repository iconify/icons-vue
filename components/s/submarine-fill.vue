<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-pjy-buk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:submarine-fill" /></template>
<style>
.z-pjy-buk {
  fill: currentColor;
  d: path("M13 6v1a2 2 0 0 1 2 2v2h2a5 5 0 0 1 0 10H9a3 3 0 0 1-3-3v-1H4v3a1 1 0 0 1-2 0v-8a1 1 0 0 1 2 0v3h2v-1a3 3 0 0 1 3-3V9a2 2 0 0 1 2-2V6a3 3 0 0 1 3-3h2a1 1 0 0 1 0 2h-2a.997.997 0 0 0-1 1m-.99 9H12a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2m4 0H16a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
