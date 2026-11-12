<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h764u2gae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-lock-corner-fill" /></template>
<style>
.h764u2gae {
  fill: currentColor;
  d: path("M21 9H4v9a1 1 0 0 0 1 1h3a1 1 0 0 1 0 2H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v2a1 1 0 0 1-1 1m1 8v3a2 2 0 0 1-2 2h-6a2 2 0 0 1-2-2v-3a2 2 0 0 1 2-2a3 3 0 1 1 6 0a2 2 0 0 1 2 2m-6-2h2a1 1 0 0 0-2 0m-2 2v3h6v-3Z");
}

</style>
