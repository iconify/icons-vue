<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-expobfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-segments-bulk-round" /></template>
<style>
.v-expobfd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 6a2 2 0 0 1 2-2h5a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2Zm11 0a2 2 0 0 1 2-2h5a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2h-5a2 2 0 0 1-2-2ZM2 15a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2Zm14 0a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2h-2a2 2 0 0 1-2-2Z");
}

</style>
