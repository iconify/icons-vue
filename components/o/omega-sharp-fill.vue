<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ce_c84l0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:omega-sharp-fill" /></template>
<style>
.ce_c84l0w {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M1 21L8.2721 21L5.636 18.364C3.9482 16.6761 3 14.3869 3 12C3 7.0294 7.0294 3 12 3C16.9706 3 21 7.0294 21 12C21 14.3869 20.0518 16.6761 18.364 18.364L15.7279 21L23 21");
}

</style>
