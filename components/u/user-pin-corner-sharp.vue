<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnzl0srnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-pin-corner-sharp" /></template>
<style>
.nnzl0srnt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 7a4 4 0 1 0 8 0a4 4 0 0 0-8 0M3 21a6 6 0 0 1 6-6m6-2h4v3l2 2h-8l2-2zm-1 0h6m-3 5v3");
}

</style>
