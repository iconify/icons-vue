<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ybknrabyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-medium-fill-round" /></template>
<style>
.ybknrabyh {
  fill: currentColor;
  d: path("M10 5h4a5 5 0 0 1 5 5v4a5 5 0 0 1-1.464 3.536A5 5 0 0 1 14 19h-4a5 5 0 0 1-5-5v-4a5 5 0 0 1 5-5");
}

</style>
