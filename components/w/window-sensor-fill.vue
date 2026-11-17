<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="arxsl6lei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-sensor-fill" /></template>
<style>
.arxsl6lei {
  fill: currentColor;
  d: path("M20 11a6.99 6.99 0 0 0-7-7a1 1 0 1 1 0-2a9 9 0 0 1 9 9a1 1 0 0 1-2 0m-4 0a3 3 0 0 0-3-3a1.002 1.002 0 0 1-.866-1.5c.179-.309.509-.5.866-.5c1.33 0 2.597.522 3.536 1.464A5 5 0 0 1 18 11a1 1 0 0 1-2 0M5 10h6a3 3 0 0 1 3 3v6a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3v-6a3 3 0 0 1 3-3m0 2a1 1 0 0 0-1 1v2h3v-3Zm4 3h3v-2a1 1 0 0 0-1-1H9Zm-2 2H4v2a1 1 0 0 0 1 1h2Zm2 0v3h2a1 1 0 0 0 1-1v-2Z");
}

</style>
