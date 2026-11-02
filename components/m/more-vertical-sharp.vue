<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i82rs5bju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:more-vertical-sharp" /></template>
<style>
.i82rs5bju {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 6a1 1 0 1 0 2 0a1 1 0 0 0-2 0m0 6a1 1 0 1 0 2 0a1 1 0 0 0-2 0m0 6a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
