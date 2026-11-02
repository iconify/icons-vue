<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpba0owpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:school" /></template>
<style>
.tpba0owpf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m4 7l8-4l8 4M6 6v5l-3 2v6a2 2 0 0 0 2 2h14a2 2 0 0 0 2-2v-6l-3-2V6m-8 4a2 2 0 1 0 4 0a2 2 0 0 0-4 0m0 11v-3a2 2 0 1 1 4 0v3");
}

</style>
