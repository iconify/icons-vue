<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsfh4przo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-arrow-left" /></template>
<style>
.lsfh4przo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 6V5a2 2 0 0 1 2-2h1m12 0h1a2 2 0 0 1 2 2v1m0 12v1a2 2 0 0 1-2 2h-1M6 21H5a2 2 0 0 1-2-2v-1m7-15h4m7 7v4m-7 7h-4m-7-7v-4m8-1l-3 3l3 3m-3-3h8");
}

</style>
