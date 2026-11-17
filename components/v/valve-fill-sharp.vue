<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uyhg2kopr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:valve-fill-sharp" /></template>
<style>
.uyhg2kopr {
  fill: currentColor;
  d: path("M15 4a1 1 0 0 1 0 2h-2v2h3a1 1 0 0 1 1 1v2h3v-1a1 1 0 0 1 2 0v8a1 1 0 0 1-2 0v-1h-3v2a1 1 0 0 1-1 1H8a1 1 0 0 1-1-1v-2H4v1a1 1 0 0 1-2 0v-8a1 1 0 0 1 2 0v1h3V9a1 1 0 0 1 1-1h3V6H9a1 1 0 0 1 0-2Z");
}

</style>
