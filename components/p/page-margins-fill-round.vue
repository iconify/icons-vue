<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fl9mc7bfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:page-margins-fill-round" /></template>
<style>
.fl9mc7bfa {
  fill: currentColor;
  d: path("M9 2h6a5 5 0 0 1 5 5v10a5 5 0 0 1-1.464 3.536A5 5 0 0 1 15 22H9a5 5 0 0 1-5-5V7a5 5 0 0 1 5-5m2 6a1 1 0 0 0-1 1v6a1 1 0 0 0 1 1h2a1 1 0 0 0 1-1V9a1 1 0 0 0-1-1Z");
}

</style>
