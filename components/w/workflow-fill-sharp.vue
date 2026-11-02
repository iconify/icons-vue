<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pftyt_bzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:workflow-fill-sharp" /></template>
<style>
.pftyt_bzi {
  fill: currentColor;
  d: path("M11 2a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1H8v4h4v-3a1 1 0 0 1 1-1h8a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1h-8a1 1 0 0 1-1-1v-3H7a1 1 0 0 1-1-1v-5H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1Z");
}

</style>
