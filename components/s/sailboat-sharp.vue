<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwsyhya9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sailboat-sharp" /></template>
<style>
.qwsyhya9t {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 16L22 16L18 22L6 22ZM12 2L20 12L12 12ZM12 5L5 12L12 12M12 12L12 16");
}

</style>
