<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i-irvsb2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:target-16-filled" /></template>
<style>
.i-irvsb2p {
  fill: currentColor;
  d: path("M8 9a1 1 0 1 0 0-2a1 1 0 0 0 0 2M4.5 8a3.5 3.5 0 1 1 7 0a3.5 3.5 0 0 1-7 0M8 6a2 2 0 1 0 0 4a2 2 0 0 0 0-4M2 8a6 6 0 1 1 12 0A6 6 0 0 1 2 8m6-4.5a4.5 4.5 0 1 0 0 9a4.5 4.5 0 0 0 0-9");
}

</style>
