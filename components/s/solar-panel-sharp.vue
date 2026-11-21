<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxe1ffbsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:solar-panel-sharp" /></template>
<style>
.mxe1ffbsi {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 3L18 3L22 15L2 15ZM10 3L8.6667 15M14 3L15.3333 15M4 9L20 9M12 15L12 21M7 21L17 21");
}

</style>
