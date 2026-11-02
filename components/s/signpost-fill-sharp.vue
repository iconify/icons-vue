<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dpfd5x4dp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:signpost-fill-sharp" /></template>
<style>
.dpfd5x4dp {
  fill: currentColor;
  d: path("M13 5h4c.265 0 .52.105.707.293l3 3a1 1 0 0 1 0 1.414l-3 3A1 1 0 0 1 17 13h-4v8a1 1 0 0 1-2 0v-8H4a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1h7V3a1 1 0 0 1 2 0Z");
}

</style>
