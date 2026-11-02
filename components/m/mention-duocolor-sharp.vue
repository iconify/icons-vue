<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lf6m0mjdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mention-duocolor-sharp" /></template>
<style>
.lf6m0mjdi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 12v1a2 2 0 1 0 4 0a7.071 7.071 0 1 0-6 6m-4-7a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

</style>
