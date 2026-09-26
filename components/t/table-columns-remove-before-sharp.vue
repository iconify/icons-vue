<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6dh9ccam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-columns-remove-before-sharp" /></template>
<style>
.i6dh9ccam {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 18L4 21L22 21L22 3L4 3L4 6M13 21L13 3M1.7071 8.7071L8.2929 15.2929M8.2929 8.7071L1.7071 15.2929");
}

</style>
