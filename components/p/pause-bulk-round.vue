<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="erehkzbrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pause-bulk-round" /></template>
<style>
.erehkzbrg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 5a3 3 0 0 1 3-3h1a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3Zm11 0a3 3 0 0 1 3-3h1a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3h-1a3 3 0 0 1-3-3Z");
}

</style>
