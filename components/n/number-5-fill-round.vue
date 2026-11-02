<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2jy7ccqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:number-5-fill-round" /></template>
<style>
.d2jy7ccqw {
  fill: currentColor;
  d: path("M9 5v5h3a6 6 0 1 1-6 6a1 1 0 0 1 2 0a4 4 0 1 0 4-4H8a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1h8a1 1 0 0 1 0 2Z");
}

</style>
