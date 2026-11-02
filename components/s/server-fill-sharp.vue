<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qab42cb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-fill-sharp" /></template>
<style>
.qab42cb6h {
  fill: currentColor;
  d: path("M3 3h18a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1m4 3a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm-4 7h18a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-6a1 1 0 0 1 1-1m4 3a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Z");
}

</style>
