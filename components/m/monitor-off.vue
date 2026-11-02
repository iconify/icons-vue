<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbdt-h8in"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:monitor-off" /></template>
<style>
.nbdt-h8in {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18 17H6a2 2 0 0 1-2-2V6c0-.811.306-1.686 1-2m6 0h7a2 2 0 0 1 2 2v7M9 20h6M3 2l19 19");
}

</style>
