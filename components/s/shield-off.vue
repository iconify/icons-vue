<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bl0o7xu2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-off" /></template>
<style>
.bl0o7xu2w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 3h8a2 2 0 0 1 2 2v5c0 .958.2 1.16 0 2m-2 5c-1.441 1.847-3.721 2.987-6 4c-4.5-2-8-5.5-8-11V5c0-.552.638-.638 1-1M3 2l19 19");
}

</style>
