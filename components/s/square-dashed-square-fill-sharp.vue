<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0q2f4o5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-square-fill-sharp" /></template>
<style>
.a0q2f4o5p {
  fill: currentColor;
  d: path("M2 3a1 1 0 0 1 1-1h3a1 1 0 0 1 0 2H4v2a1 1 0 0 1-2 0Zm12-1a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2Zm7 0a1 1 0 0 1 1 1v3a1 1 0 0 1-2 0V4h-2a1 1 0 0 1 0-2ZM2 21V10a1 1 0 0 1 1-1h11a1 1 0 0 1 1 1v11a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1m20-7a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0Zm0 7a1 1 0 0 1-1 1h-3a1 1 0 0 1 0-2h2v-2a1 1 0 0 1 2 0Z");
}

</style>
