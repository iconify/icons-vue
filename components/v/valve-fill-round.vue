<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sekwasb5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:valve-fill-round" /></template>
<style>
.sekwasb5k {
  fill: currentColor;
  d: path("M15 4a1 1 0 0 1 0 2h-2v2h1a3 3 0 0 1 3 3h3v-1a1 1 0 0 1 2 0v8a1 1 0 0 1-2 0v-1h-3a3 3 0 0 1-3 3h-4a3 3 0 0 1-3-3H4v1a1 1 0 0 1-2 0v-8a1 1 0 0 1 2 0v1h3a3 3 0 0 1 3-3h1V6H9a1 1 0 0 1 0-2Z");
}

</style>
