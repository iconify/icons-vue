<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmng4ab-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-check-corner-round" /></template>
<style>
.nmng4ab-v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 7a3 3 0 0 1 3-3h12a3 3 0 0 1 0 6H6a3 3 0 0 1-3-3m0 7h6m0 6H6a3 3 0 0 1-3-3v-3m4-7h.01M7 17h.01M13 17l3 3l5-6");
}

</style>
