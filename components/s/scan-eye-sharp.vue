<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="od8u2xbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scan-eye-sharp" /></template>
<style>
.od8u2xbzy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 7V3h4m10 0h4v4m0 10v4h-4M7 21H3v-4m2-5c4-6 10-6 14 0c-4 6-10 6-14 0m7 0h.01");
}

</style>
