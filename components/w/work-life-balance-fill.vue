<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kr5ntl30l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:work-life-balance-fill" /></template>
<style>
.kr5ntl30l {
  fill: currentColor;
  d: path("M4 5V4a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v1a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2m4-1H6v1h2Zm10 1.207a2.8 2.8 0 0 1 1.874-.449a2.4 2.4 0 0 1 1.502.779c.437.498.624 1.142.624 1.796c0 .702-.252 1.372-.628 1.958c-.586.911-1.453 1.652-2.349 2.249a8 8 0 0 1-.537.334a1 1 0 0 1-.972 0a8 8 0 0 1-.537-.334c-1.394-.929-2.976-2.407-2.977-4.207c0-.654.187-1.298.624-1.796a2.4 2.4 0 0 1 1.502-.779A2.8 2.8 0 0 1 18 5.207M3 14h18a1 1 0 0 1 0 2h-8v4h3a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2h3v-4H3a1 1 0 0 1 0-2");
}

</style>
