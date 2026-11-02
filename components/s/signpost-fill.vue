<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpu4kac0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:signpost-fill" /></template>
<style>
.cpu4kac0j {
  fill: currentColor;
  d: path("M13 5h3c1.039 0 1.992.578 2.707 1.293l1 1a2.414 2.414 0 0 1 0 3.414l-1 1C17.992 12.422 17.039 13 16 13h-3v8a1 1 0 0 1-2 0v-8H6a3 3 0 0 1-3-3V8a3 3 0 0 1 3-3h5V3a1 1 0 0 1 2 0Z");
}

</style>
