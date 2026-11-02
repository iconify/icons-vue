<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhi3rlo9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:slider-vertical-3-fill-round" /></template>
<style>
.lhi3rlo9u {
  fill: currentColor;
  d: path("M7 3v6h1a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2h1V3a1 1 0 0 1 2 0m7 12a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2h1V3a1 1 0 0 1 2 0v12Zm5-12v3h1a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2h1V3a1 1 0 0 1 2 0m0 18a1 1 0 0 1-2 0V11a1 1 0 0 1 2 0ZM7 14v7a1 1 0 0 1-2 0v-7a1 1 0 0 1 2 0m6 6v1a1 1 0 0 1-2 0v-1a1 1 0 0 1 2 0");
}

</style>
