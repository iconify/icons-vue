<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxosvw3ix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-minus-sharp" /></template>
<style>
.fxosvw3ix {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 7L23 7M8 14L10 14C13.3137 14 16 16.6863 16 20L16 21L2 21L2 20C2 16.6863 4.6863 14 8 14ZM9 4C10.6569 4 12 5.3431 12 7C12 8.6569 10.6569 10 9 10C7.3431 10 6 8.6569 6 7C6 5.3431 7.3431 4 9 4Z");
}

</style>
