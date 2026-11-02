<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kd8dcdbro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pizza-round" /></template>
<style>
.kd8dcdbro {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m4 19l8-16l8 16a17 17 0 0 1-16 0m14-4a12.53 12.53 0 0 1-12 0m6-5h.01M11 13h.01");
}

</style>
