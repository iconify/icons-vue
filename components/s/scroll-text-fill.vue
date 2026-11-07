<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u4ct_bqpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scroll-text-fill" /></template>
<style>
.u4ct_bqpx {
  fill: currentColor;
  d: path("M16 2a3 3 0 0 1 3 3v11h1a2 2 0 0 1 2 2v1a3 3 0 0 1-3 3H9a3 3 0 0 1-3-3V9H4a2 2 0 0 1-2-2V5a3 3 0 0 1 3-3ZM6 5a1 1 0 0 0-2 0v1a1 1 0 0 0 2 0Zm9 2h-5a1 1 0 0 0 0 2h5a1 1 0 0 0 0-2m0 4h-5a1 1 0 0 0 0 2h5a1 1 0 0 0 0-2m4 9a1 1 0 0 0 0-2h-6a1 1 0 0 0 0 2Z");
}

</style>
