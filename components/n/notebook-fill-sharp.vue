<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9qkd3bxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:notebook-fill-sharp" /></template>
<style>
.w9qkd3bxw {
  fill: currentColor;
  d: path("M3 20V4a1 1 0 0 1 1-1h16a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1m6-1h10V5H9Zm7-12a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2Zm0 4a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2Z");
}

</style>
