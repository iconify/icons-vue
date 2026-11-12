<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="honpqjh6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-warning-corner-sharp" /></template>
<style>
.honpqjh6d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 4h18v6H3Zm0 10h6m0 6H3v-6m4-7h.01M7 17h.01M17 14v4m0 3h.01");
}

</style>
