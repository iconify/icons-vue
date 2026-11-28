<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sfr2_1fjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-check-sharp" /></template>
<style>
.sfr2_1fjt {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.7016 5.6644L18 8.25L22.2526 3.4659M8 13L10 13C13.3137 13 16 15.6863 16 19L16 21L2 21L2 19C2 15.6863 4.6863 13 8 13ZM9 3C10.6569 3 12 4.3431 12 6C12 7.6569 10.6569 9 9 9C7.3431 9 6 7.6569 6 6C6 4.3431 7.3431 3 9 3Z");
}

</style>
