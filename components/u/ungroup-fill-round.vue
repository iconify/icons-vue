<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ule40toop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ungroup-fill-round" /></template>
<style>
.ule40toop {
  fill: currentColor;
  d: path("M10 4a3 3 0 0 1 3 3v1a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3Zm7 9a3 3 0 0 1 3 3v1a3 3 0 0 1-3 3h-3a3 3 0 0 1-3-3v-1a3 3 0 0 1 3-3Z");
}

</style>
