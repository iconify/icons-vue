<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1zu28dvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ticket-fill-round" /></template>
<style>
.d1zu28dvw {
  fill: currentColor;
  d: path("M13 19H6a4 4 0 0 1-4-4a1 1 0 0 1 1-1a2 2 0 1 0 0-4a1 1 0 0 1-1-1a4 4 0 0 1 4-4h7Zm2 0V5h3a4 4 0 0 1 4 4a1 1 0 0 1-1 1a2 2 0 1 0 0 4a1 1 0 0 1 1 1a4 4 0 0 1-4 4Z");
}

</style>
