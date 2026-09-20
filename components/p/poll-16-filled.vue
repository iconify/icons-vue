<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g84hw2bma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:poll-16-filled" /></template>
<style>
.g84hw2bma {
  fill: currentColor;
  d: path("M6 3a2 2 0 1 1 4 0v10a2 2 0 1 1-4 0zM1 9a2 2 0 1 1 4 0v4a2 2 0 1 1-4 0zm10-2a2 2 0 1 1 4 0v6a2 2 0 1 1-4 0z");
}

</style>
