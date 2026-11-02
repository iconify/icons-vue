<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xkz6_v_rf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shift-bulk-sharp" /></template>
<style>
.xkz6_v_rf {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15 20H9a1 1 0 0 1-1-1v-5H4a1.002 1.002 0 0 1-.707-1.707l8-8a1 1 0 0 1 1.414 0l8 8A1 1 0 0 1 20 14h-4v5a1 1 0 0 1-1 1");
}

</style>
