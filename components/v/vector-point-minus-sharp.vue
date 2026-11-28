<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nljjvmupc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:vector-point-minus-sharp" /></template>
<style>
.nljjvmupc {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 9L13 9L13 13L9 13ZM2 20L2 19C2 15 5 11 9 11M13 11C17 11 22 9 22 5L22 4M15 19L23 19");
}

</style>
