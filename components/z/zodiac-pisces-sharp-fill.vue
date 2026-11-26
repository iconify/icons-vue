<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wsan6lbyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:zodiac-pisces-sharp-fill" /></template>
<style>
.wsan6lbyd {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 3L3 3C6.8802 4.2851 9.5 7.9125 9.5 12C9.5 16.0875 6.8802 19.7149 3 21L2 21M22 3L21 3C17.1198 4.2851 14.5 7.9125 14.5 12C14.5 16.0875 17.1198 19.7149 21 21L22 21M4 12L20 12");
}

</style>
