<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oijkm1car"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:poll-16-regular" /></template>
<style>
.oijkm1car {
  fill: currentColor;
  d: path("M8 1a2 2 0 0 0-2 2v10a2 2 0 1 0 4 0V3a2 2 0 0 0-2-2m1 2v10a1 1 0 1 1-2 0V3a1 1 0 0 1 2 0M3 7a2 2 0 0 0-2 2v4a2 2 0 1 0 4 0V9a2 2 0 0 0-2-2m1 6a1 1 0 1 1-2 0V9a1 1 0 0 1 2 0zm7-6a2 2 0 1 1 4 0v6a2 2 0 1 1-4 0zm3 0a1 1 0 1 0-2 0v6a1 1 0 1 0 2 0z");
}

</style>
