<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjd5vkbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:row-minus-fill-sharp" /></template>
<style>
.qjd5vkbcz {
  fill: currentColor;
  d: path("M3 10V4a1 1 0 0 1 1-1h16a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1m12 6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2Z");
}

</style>
