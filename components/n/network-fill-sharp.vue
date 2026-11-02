<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d4n19yb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:network-fill-sharp" /></template>
<style>
.d4n19yb2m {
  fill: currentColor;
  d: path("M15 2a1 1 0 0 1 1 1v5a1 1 0 0 1-1 1h-2v2h5a1 1 0 0 1 1 1v3h2a1 1 0 0 1 1 1v5a1 1 0 0 1-1 1h-6a1 1 0 0 1-1-1v-5a1 1 0 0 1 1-1h2v-2H7v2h2a1 1 0 0 1 1 1v5a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-5a1 1 0 0 1 1-1h2v-3a1 1 0 0 1 1-1h5V9H9a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1Z");
}

</style>
