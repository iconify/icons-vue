<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3tfzwbzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:subnet-sharp" /></template>
<style>
.z3tfzwbzx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 11h18v10H3Zm7-6a2 2 0 1 0 4 0a2 2 0 0 0-4 0M7 16h.01M12 16h.01M17 16h.01M12 7v4");
}

</style>
