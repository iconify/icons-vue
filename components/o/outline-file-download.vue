<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dfxbux11t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-file-download" /></template>
<style>
.dfxbux11t {
  fill: currentColor;
  d: path("M18 15v3H6v-3H4v3c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2v-3zm-1-4l-1.41-1.41L13 12.17V4h-2v8.17L8.41 9.59L7 11l5 5z");
}

</style>
