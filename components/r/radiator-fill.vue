<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ile8nubpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:radiator-fill" /></template>
<style>
.ile8nubpz {
  fill: currentColor;
  d: path("M7 4v3h3V4a2 2 0 1 1 4 0v3h3V4a2 2 0 1 1 4 0v11a1 1 0 0 1 0 2v3a2 2 0 1 1-4 0v-3h-3v3a2 2 0 1 1-4 0v-3H7v3a2 2 0 1 1-4 0V9a1 1 0 0 1 0-2V4a2 2 0 1 1 4 0m0 11h3V9H7Zm7 0h3V9h-3Z");
}

</style>
