<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z4ly2pbud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:vector-polygon-sharp" /></template>
<style>
.z4ly2pbud {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 2L14 2L14 6L10 6ZM18 8L22 8L22 12L18 12ZM15 18L19 18L19 22L15 22ZM5 18L9 18L9 22L5 22ZM2 8L6 8L6 12L2 12ZM14 5.5L18 8.5M19.4 12L17.6 18M15 20L9 20M6.4 18L4.6 12M6 8.5L10 5.5");
}

</style>
