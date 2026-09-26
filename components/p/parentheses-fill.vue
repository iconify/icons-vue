<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vg_p6bmic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:parentheses-fill" /></template>
<style>
.vg_p6bmic {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 2C5.4322 4.6962 4 8.2767 4 12C4 15.7233 5.4322 19.3038 8 22M16 2C18.5678 4.6962 20 8.2767 20 12C20 15.7233 18.5678 19.3038 16 22");
}

</style>
