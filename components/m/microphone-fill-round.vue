<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7a5fxbal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:microphone-fill-round" /></template>
<style>
.d7a5fxbal {
  fill: currentColor;
  d: path("M8 6a4 4 0 0 1 8 0v5a4 4 0 0 1-8 0Zm-2 5a6 6 0 1 0 12 0v-1a1 1 0 0 1 2 0v1a8.006 8.006 0 0 1-7 7.939V21a1 1 0 0 1-2 0v-2.061A8.006 8.006 0 0 1 4 11v-1a1 1 0 0 1 2 0Z");
}

</style>
