<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8bqnxjps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-minus-fill-sharp" /></template>
<style>
.a8bqnxjps {
  fill: currentColor;
  d: path("M2 20V4a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1m2-1h16V9H4Zm5-6h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2");
}

</style>
