<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxvnnxqwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:plus-forward-slash-minus-sharp" /></template>
<style>
.rxvnnxqwu {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 18H23M1 6H5.999M5.999 6H11M5.999 6L5.997 11M5.999 6L6 1M4.701 22.43L19.299 1.57");
}

</style>
