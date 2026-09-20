<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bupg7kupl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:poll-horizontal-16-filled" /></template>
<style>
.bupg7kupl {
  fill: currentColor;
  d: path("M13 6a2 2 0 1 1 0 4H3a2 2 0 1 1 0-4zM7 1a2 2 0 1 1 0 4H3a2 2 0 1 1 0-4zm2 10a2 2 0 1 1 0 4H3a2 2 0 1 1 0-4z");
}

</style>
