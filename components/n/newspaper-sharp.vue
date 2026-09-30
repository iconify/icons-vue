<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t0zgv8urq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:newspaper-sharp" /></template>
<style>
.t0zgv8urq {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 3L21 3L21 21L3 21L3 9L8 9L8 3ZM8 9L8 21M11 8L18 8M11 12L18 12M11 16L16 16");
}

</style>
