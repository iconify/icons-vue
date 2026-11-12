<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfc_9ab2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-arrow-left-duotone-sharp" /></template>
<style>
.pfc_9ab2s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 6V3h3m12 0h3v3m0 12v3h-3M6 21H3v-3m7-15h4m7 7v4m-7 7h-4m-7-7v-4m8-1l-3 3l3 3m-3-3h8");
}

</style>
