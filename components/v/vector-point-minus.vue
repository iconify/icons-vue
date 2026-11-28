<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lh-ktgfqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:vector-point-minus" /></template>
<style>
.lh-ktgfqf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 9L12 9C12.5523 9 13 9.4477 13 10L13 12C13 12.5523 12.5523 13 12 13L10 13C9.4477 13 9 12.5523 9 12L9 10C9 9.4477 9.4477 9 10 9ZM2 19C2 15 5 11 9 11M13 11C17 11 22 9 22 5M16 19L22 19");
}

</style>
