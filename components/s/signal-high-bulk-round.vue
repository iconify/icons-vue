<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yugmclm0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:signal-high-bulk-round" /></template>
<style>
.yugmclm0w {
  fill: currentColor;
  d: path("M19 4v16a1 1 0 0 1-2 0V4a1 1 0 0 1 2 0m-6 4a1 1 0 0 1 2 0v12a1 1 0 0 1-2 0Zm-4 4a1 1 0 0 1 2 0v8a1 1 0 0 1-2 0Zm-4 4a1 1 0 0 1 2 0v4a1 1 0 0 1-2 0Z");
}

</style>
