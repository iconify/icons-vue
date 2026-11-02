<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9p-hhoeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-check-fill-sharp" /></template>
<style>
.s9p-hhoeb {
  fill: currentColor;
  d: path("M2 6V3a1 1 0 0 1 1-1h3a1 1 0 0 1 0 2H4v2a1 1 0 0 1-2 0m8-4h4a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2m8 0h3a1 1 0 0 1 1 1v3a1 1 0 0 1-2 0V4h-2a1 1 0 0 1 0-2m-9.293 9.293l2.226 2.226l4.299-5.159a1 1 0 1 1 1.536 1.28l-5 6a1 1 0 0 1-1.475.067l-3-3a.999.999 0 1 1 1.414-1.414M2 14v-4a1 1 0 0 1 2 0v4a1 1 0 0 1-2 0m20-4v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0M6 22H3a1 1 0 0 1-1-1v-3a1 1 0 0 1 2 0v2h2a1 1 0 0 1 0 2m16-4v3a1 1 0 0 1-1 1h-3a1 1 0 0 1 0-2h2v-2a1 1 0 0 1 2 0m-8 4h-4a1 1 0 0 1 0-2h4a1 1 0 0 1 0 2");
}

</style>
