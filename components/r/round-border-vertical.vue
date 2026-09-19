<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pca-kzbmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-border-vertical" /></template>
<style>
.pca-kzbmz {
  fill: currentColor;
  d: path("M3 9h2V7H3zm0-4h2V3H3zm4 16h2v-2H7zm0-8h2v-2H7zm-4 0h2v-2H3zm0 8h2v-2H3zm0-4h2v-2H3zM7 5h2V3H7zm12 12h2v-2h-2zm-7 4c.55 0 1-.45 1-1V4c0-.55-.45-1-1-1s-1 .45-1 1v16c0 .55.45 1 1 1m7 0h2v-2h-2zm0-8h2v-2h-2zm0-10v2h2V3zm0 6h2V7h-2zm-4-4h2V3h-2zm0 16h2v-2h-2zm0-8h2v-2h-2z");
}

</style>
