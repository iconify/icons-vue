<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x08lzcctq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tram-side-fill" /></template>
<style>
.x08lzcctq {
  fill: currentColor;
  d: path("M15 2a1 1 0 0 1 0 2h-2v2h6a3 3 0 0 1 3 3v6a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V9a3 3 0 0 1 3-3h6V4H9a1 1 0 0 1 0-2ZM7 8H5a1 1 0 0 0-1 1v2h3Zm2 0v3h3V8Zm11 1a1 1 0 0 0-1-1h-5v3h6Zm1 11a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Z");
}

</style>
