<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mu868uvmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:network-split-sharp" /></template>
<style>
.mu868uvmm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 5a2 2 0 1 0 4 0a2 2 0 0 0-4 0m2 2v5m-6 8v-8h12v8M3 17l3 3l3-3m6 0l3 3l3-3");
}

</style>
