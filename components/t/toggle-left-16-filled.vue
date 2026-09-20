<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h_36vdbri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:toggle-left-16-filled" /></template>
<style>
.h_36vdbri {
  fill: currentColor;
  d: path("M11 4a4 4 0 0 1 0 8H5a4 4 0 0 1 0-8zm-6 6a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

</style>
