<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmgy946rg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pin-off-sharp" /></template>
<style>
.cmgy946rg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 3h5a2 2 0 1 1 0 4a1 1 0 0 0-.707.293m3.414 9.414A1 1 0 0 1 18 17H6a1 1 0 0 1-1-1v-1c0-2 4-2 4-4V8a1 1 0 0 0-1-1a2 2 0 0 1-1.823-2.823M12 17v4M4 2l18 18");
}

</style>
