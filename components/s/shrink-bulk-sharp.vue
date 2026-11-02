<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wrgo91_7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shrink-bulk-sharp" /></template>
<style>
.wrgo91_7r {
  fill: currentColor;
  d: path("M14 11a1 1 0 0 1-1-1V4a1 1 0 0 1 2 0v5h5a1 1 0 0 1 0 2Zm-4 2a1 1 0 0 1 1 1v6a1 1 0 0 1-2 0v-5H4a1 1 0 0 1 0-2Z");
}

</style>
