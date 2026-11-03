<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zb2daqbzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:repeat-off-fill" /></template>
<style>
.zb2daqbzf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 12L3 9C3 7.3432 4.3431 6 6 6M18 18L3 18M6 21L3 18L6 15M11.6569 6L21 6M18 3L21 6L18 9M21 12L21 15C21 15.11 20.9941 15.2187 20.9825 15.3257M2 2L22 22");
}

</style>
