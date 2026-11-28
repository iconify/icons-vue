<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twjhlexoz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:scan-plus-fill" /></template>
<style>
.twjhlexoz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 8L3 6C3 4.34315 4.34315 3 6 3L8 3M16 3L18 3C19.6569 3 21 4.34315 21 6L21 8M8 21L6 21C4.34315 21 3 19.6569 3 18L3 16M18 15L18 21M15 18L21 18");
}

</style>
