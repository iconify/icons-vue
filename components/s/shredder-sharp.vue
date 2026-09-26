<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tgv48hb8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shredder-sharp" /></template>
<style>
.tgv48hb8j {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 12L4 2L14 2L20 8L20 12M14 2L14 8L20 8M1 12L23 12M6 15L6 23M10 15L10 21M14 15L14 23M18 15L18 21");
}

</style>
