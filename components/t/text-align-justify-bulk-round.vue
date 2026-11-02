<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0yu7z-4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-align-justify-bulk-round" /></template>
<style>
.o0yu7z-4s {
  fill: currentColor;
  d: path("M20 5a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2Zm0 4a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2Zm0 4a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2Zm0 4a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2Z");
}

</style>
