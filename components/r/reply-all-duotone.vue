<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cayi-4dcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:reply-all-duotone" /></template>
<style>
.cayi-4dcn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 5L3 9l4 4m6-8L9 9l4 4M3 9h16a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2h-8");
}

</style>
