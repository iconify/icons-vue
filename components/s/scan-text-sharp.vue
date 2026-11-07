<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="abt2_xbzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scan-text-sharp" /></template>
<style>
.abt2_xbzq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 7V3h4m10 0h4v4m0 10v4h-4M7 21H3v-4m4-9h10M7 12h10M7 16h6");
}

</style>
