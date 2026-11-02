<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhqzp3rmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-square-top-left-fill" /></template>
<style>
.dhqzp3rmn {
  fill: currentColor;
  d: path("M2 5a3 3 0 0 1 3-3h7a3 3 0 0 1 3 3v7a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm17-3a3 3 0 0 1 3 3v1a1 1 0 0 1-2 0V5a1 1 0 0 0-1-1h-1a1 1 0 0 1 0-2Zm1 12v-4a1 1 0 0 1 2 0v4a1 1 0 0 1-2 0M5 22a3 3 0 0 1-3-3v-1a1 1 0 0 1 2 0v1a1 1 0 0 0 1 1h1a1 1 0 0 1 0 2Zm17-3a3 3 0 0 1-3 3h-1a1 1 0 0 1 0-2h1a1 1 0 0 0 1-1v-1a1 1 0 0 1 2 0Zm-12 1h4a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2");
}

</style>
