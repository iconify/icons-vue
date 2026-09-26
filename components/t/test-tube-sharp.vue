<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxcqmib8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:test-tube-sharp" /></template>
<style>
.dxcqmib8r {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 2L15 2L15 19C15 20.6569 13.6569 22 12 22C10.3431 22 9 20.6569 9 19L9 2ZM7 2L17 2M9 14L15 14");
}

</style>
