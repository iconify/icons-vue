<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="of-hs-v5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:washing-machine-sharp" /></template>
<style>
.of-hs-v5e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 3h16v18H4Zm0 6h16M8 6h.01M11 6h.01M9 15a3 3 0 0 1 6 0m0 0a3 3 0 0 1-6 0");
}

</style>
