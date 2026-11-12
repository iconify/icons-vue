<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="w3r9-bcte"/><path class="yothtr4_z"/><path class="kp_4ybcux"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-underline-circle-linear" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kp_4ybcux {
  stroke-linejoin: round;
  d: path("M8 7V10C8 12.2091 9.79086 14 12 14C14.2091 14 16 12.2091 16 10V7");
}

.w3r9-bcte {
  d: path("M12 22C6.47715 22 2 17.5228 2 12C2 6.47715 6.47715 2 12 2C17.5228 2 22 6.47715 22 12C22 17.5228 17.5228 22 12 22Z");
}

.yothtr4_z {
  stroke-linejoin: round;
  d: path("M8 17H16");
}

</style>
