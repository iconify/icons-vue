<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrjx9kb7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:thumbs-down" /></template>
<style>
.qrjx9kb7x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 14a4 4 0 0 1 4 4v1a2 2 0 1 0 4 0v-3a2 2 0 0 1 2-2h2a2 2 0 0 0 2-2v-2l-2-6c-.2-.597-1.005-1-2-1H9a2 2 0 0 0-2 2m0 9H5a2 2 0 0 1-2-2V5a2 2 0 1 1 4 0z");
}

</style>
