<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="no45gcb8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:snorkel-sharp" /></template>
<style>
.no45gcb8w {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 8L18 8L18 15L12.5 15L10.5 13L9.5 13L7.5 15L2 15ZM22 4L22 19L10 19L9 19");
}

</style>
