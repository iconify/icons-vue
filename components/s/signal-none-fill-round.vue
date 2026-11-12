<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hyf7q8bkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:signal-none-fill-round" /></template>
<style>
.hyf7q8bkm {
  fill: currentColor;
  d: path("M6.01 19a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2Zm4 0a1 1 0 0 1 0 2H10a1 1 0 0 1 0-2Zm4 0a1 1 0 0 1 0 2H14a1 1 0 0 1 0-2Zm4 0a1 1 0 0 1 0 2H18a1 1 0 0 1 0-2Z");
}

</style>
