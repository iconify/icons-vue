<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k56d62gzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-bulk" /></template>
<style>
.k56d62gzl {
  fill: currentColor;
  d: path("M5 5a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v1a1 1 0 0 1-2 0h-4v12h1a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2h1V6H7a1 1 0 0 1-2 0Z");
}

</style>
