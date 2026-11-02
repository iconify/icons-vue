<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rzt8599ue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:network-fill" /></template>
<style>
.rzt8599ue {
  fill: currentColor;
  d: path("M10 2h4a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2h-1v2h3a3 3 0 0 1 3 3v1h1a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2h-4a2 2 0 0 1-2-2v-3a2 2 0 0 1 2-2h1v-1a1 1 0 0 0-1-1H8a.997.997 0 0 0-1 1v1h1a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2v-3a2 2 0 0 1 2-2h1v-1a3 3 0 0 1 3-3h3V9h-1a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2");
}

</style>
