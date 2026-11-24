<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iul0pwpmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:town-hall-fill-sharp" /></template>
<style>
.iul0pwpmq {
  fill: currentColor;
  d: path("M21 22h-6v-5a1 1 0 0 0-1-1h-4a1 1 0 0 0-1 1v5H3a1 1 0 0 1-1-1v-6a1 1 0 0 1 1-1h3V8a6 6 0 1 1 12 0v6h3a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1M13 7V6a1 1 0 0 0-2 0v2a1 1 0 0 0 1 1h2a1 1 0 0 0 0-2Zm-2 15v-4h2v4Z");
}

</style>
