<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofhs6k5it"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:robot-fill-round" /></template>
<style>
.ofhs6k5it {
  fill: currentColor;
  d: path("M13 5.733V8h2a5 5 0 0 1 5 5v1h1a1 1 0 0 1 0 2h-1v1a5 5 0 0 1-1.464 3.536A5 5 0 0 1 15 22H9a5 5 0 0 1-5-5v-1H3a1 1 0 0 1 0-2h1v-1a5 5 0 0 1 5-5h2V5.733a2.001 2.001 0 1 1 2 0M10 15v-2a1 1 0 0 0-2 0v2a1 1 0 0 0 2 0m6 0v-2a1 1 0 0 0-2 0v2a1 1 0 0 0 2 0");
}

</style>
