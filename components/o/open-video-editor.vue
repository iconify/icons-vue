<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lqdho2bwl"/><path class="aovo1jbds"/><path class="g6x1nvv6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:open-video-editor" /></template>
<style>
.aovo1jbds {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 28.197V12.434a3.144 3.144 0 0 0-3.145-3.144h-5.577l4.13 6.016H32.76L28.63 9.29h-4.14l4.14 6.016h-5.145l-4.14-6.016h-4.13l4.13 6.016h-5.147L10.07 9.29H8.646A3.144 3.144 0 0 0 5.5 12.434v23.132a3.144 3.144 0 0 0 3.144 3.144h18.238");
}

.g6x1nvv6h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.247 25.935v-7.543l-30.494.042v14.71c.073.879-.327 2.244.784 2.601l.083.011l.104.014l18.218.026");
}

.lqdho2bwl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.53 26.34c1.004-.843 2.568-.68 3.41.325s.723 2.527-.281 3.37l-1.603-1.877zm-10.032 7.934L38.53 26.34l1.526 1.82l1.603 1.876l-10.004 8.002m-3.157-3.762l-1.615 4.436l4.772-.674");
}

</style>
